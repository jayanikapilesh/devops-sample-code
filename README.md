# devops-sample-code

Code used by the Jenkins exercises (8 and 9) of the [DevOps Lab](https://github.com/jayanikapilesh/Devops_lab) repository. Jenkins clones this repository and runs the files below.

| File | Used in | Purpose |
|---|---|---|
| `hello-world.sh` | Exercise 8 | Shell script run by the Jenkins Freestyle job; prints `Hello, Jenkins!` |
| `app.py` | Exercise 9 | Flask application that returns `Hello, Jenkins Multi-Stage Pipeline!` |
| `test_app.py` | Exercise 9 | Unit test that checks the Flask app returns status 200 and the expected message |
| `requirements.txt` | Exercise 9 | Python dependencies (`flask==2.1.2`) |
| `Jenkinsfile` | Exercise 9 | Multi-stage pipeline: Build, Test, Deploy, Run Application, Test Application |

Full steps, outputs and screenshots are in the DevOps Lab repository:

* [Exercise 8: Creating a "Hello World" Jenkins Job](https://github.com/jayanikapilesh/Devops_lab/tree/main/Exercise-08-Jenkins-Hello-World-Job)
* [Exercise 9: Jenkins Multi-Stage Pipeline](https://github.com/jayanikapilesh/Devops_lab/tree/main/Exercise-09-Jenkins-Multi-Stage-Pipeline)