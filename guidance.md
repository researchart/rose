# Guidance (methods, hints and tips)

## Things to Look For

This section comes from Erin Dahlgren's report: [Getting Research Software to Work:
A Case Study on Artifact Evaluation for OOPSLA 2019](https://2019.splashcon.org/getImage/orig/accpub-OOPSLA2019-licensed.pdf)


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
