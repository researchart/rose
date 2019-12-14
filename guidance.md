# Guidance (methods, hints and tips)

This document offeres some notes on the process of using Github to assign badges to SE publcaitions.

 

## Background

<img src="http://image.desktopcal.com/default/desktopcal_256x256.png" align=right>
### Goal

Artifact evaluation is a **colloborative** process where reviewers and and authors work together to double check that research
artifacts are ady to be used (or have been used) by other teams.

This is **not** an adversial process. 

- Everything we deal with here relates to materials that have passed peer review at other venues.
- Hence we expect a very large "acceptance" rate; i.e. most authors will get the badges that they request.

This is a **interactive** process where reviewers and authors may have multiple interactions; e.g.

- Reviewers point out some small issue that stops an artifact installing on a new platfrom
- Authors fix up their artifacts to remove that issue.

 ### F.A.Q: Why use Github? 

We prefer toosl like Github over tools like EasyChair, HotCrp, etc since tools like  Github allows for the colloberative interactive
process required to prepare artifacts for widespread use.



## Things to Look For

This section comes from Erin Dahlgren's repor  [Getting Research Software to Work:
A Case Study on Artifact Evaluation for OOPSLA 2019](https://2019.splashcon.org/getImage/orig/accpub-OOPSLA2019-licensed.pdf) 
and lists some common comments that reviewers make about artifacts. Reviewers may find the following comments useful in their review.


### Common Negative Comments

- Environment
  - _Not enough resources._ Reviewers didn’t have enough physical re- sources to test the artifact locally in a reasonable amount of time.
  - _Issues with software dependencies._ Reviewers struggled to find and install the right software dependencies, sometimes preventing them from setting up and testing the artifact.
  - _Works in limited environments._ Reviewers had difficulty getting access to proprietary operating systems and running benchmarks locally.
- Format
  - _Issues with VM or container._ Reviewers encountered errors when they tried to setup VM’s and containers, or the VM’s and containers slowed down the review process.
  - _Problems with docs._ Reviewers encountered typos in instructions and missing or unclear instructions.
  - _Errors in scripts._ Reviewers wasted time debugging typos and unexpected errors in helper scripts.
  - _Too complicated._ Reviewers struggled to complete complicated in- structions and to test complicated artifacts.
- Execution
  - _Long running tests._ Reviewers struggled to complete tests that took hours or days.
  - _Issues compiling or running._ Reviewers encountered errors when they tried to compile or run the artifact.
  - _Ignored errors._ Reviewers weren’t confident about artifacts that emitted errors, even if the results produced were correct.
  - _Downloads during execution._ Reviewers spent a long time running test cases that downloaded data on the fly. Reviewers were also worried that such data would not always be available.
 
### Common Positive Comments

- _Self-contained._ Reviewers were enthusiastic about artifacts that re- quired minimal setup and worked seamlessly.
- _Lightweight._ Reviewers benefited from artifacts that required minimal storage space. They also appreciated being able to download small parts of a large the artifact.
- _Comprehensive documentation_. Reviewers praised clear, easy to follow documentation that covered most if not all aspects of the artifact.
