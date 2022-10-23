# Community Software Analysis Proposal

## Software: *Gridap.jl*

*Gridap.jl* is a Julia package which implements grid-based approximations of PDEs. 
Its supported features include linear and non-linear PDEs with a variety of different finite element discretizations, as well as support for unstructured meshes.
On top of having very strong numerical capabilities, the real appeal of *Gridap.jl* is in its extremely straightforward and expressive API.
The weak form of problems can be written in a fashion which is virtually identical to the mathematical notation.

### Stats

| Description | Your answer |
|-----------------------------------------------------------|-----------|
| Repository URL                                            | [Github](https://github.com/gridap/Gridap.jl/) |
| Main/documentation website                                | [Homepage](https://gridap.github.io/Gridap.jl/dev/) |
| Year project was started                                  | 2019 |
| Number of contributors in the past year (`git shortlog -se --since=2021-10-01` may be useful) | 16 |
| Number of contributors in the lifetime of the project     | 34 |
| Number of distinct affiliations                           | Around 5, although many use personal accounts |
| Where do development discussions take place?              | Issues on Github, Slack (#gridap channel in JuliaLang slack), and Gitter  |
| Typical number of emails/comments per week?               |   |
| Typical number of commits per week?                       | Around 24 commits/week over entire project life, around 14 commits/week since 2021 |
| Typical commit size                                       | Average files changed: 3.7; average insertions: 64 lines; average deletions: 46 lines |
| How does the project accept contributions?                | Pull requests   |
| Does the project have an automated test suite?            | yes |
| Does the project use continuous integration?              | yes |
| Are any legal/licensing steps required to contribute?     | no |

### Install and run

Check the following boxes when complete or add a note below if you
encountered a problem.

- [x] I have installed the software
- [x] I have run at least one example
  - small issue: appeared to have issues when instantiating tutorials, but seems to work fine
- [x] I have run the test suite
- [x] The test suite passes
  - Passes on WSL, seems to have issues with Windows

### Notes/concerns/risks

None at this time.

### Potential Project Contributions
- Many tutorials need additional documentation (i.e. code is written, but images and descriptions of problems need to be added)
- Code coverage is okay (~88%), but could certainly be improved
