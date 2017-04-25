# tV diagonalize

A Julia exact diagonalization code for the t-V model of interacting spinless fermions in one spatial dimension with a focus on particle entanglement entropy.

This code was forked from: [MelkoCollective/BH_diagonalize](https://github.com/MelkoCollective/BH_diagonalize) which was orginally written for the bosonic Hubbard model and we have maintained a bosonic basis enumerated using the method of [Szabados et al., 2011](http://coulson.chem.elte.hu/surjan/PREPRINTS/181.pdf) with a *hard core* restriction of one particle per site.
See also [Zhang et al., 2011](http://arxiv.org/pdf/1102.4006v1.pdf).

## Requirements

* [ArgParse](https://github.com/carlobaldassi/ArgParse.jl) (`Pkg.add("ArgParse")`)
* [JeszenszkiBasis](https://github.com/0/JeszenszkiBasis.jl) (`Pkg.clone("https://github.com/0/JeszenszkiBasis.jl.git")`)


## Examples

* `julia tV_main.jl --help`
* `julia tV_main.jl --out output.dat --ee 1 --site-max 1 4 2`
* `julia tV_main_neg.jl --out output.dat --ee 1 --site-max 1 4 2`



