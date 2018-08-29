# Template for Open Research Experiment: Jspsych

This template is provided by [Open Bases](https://openbases.github.io) and 
will create a submission for Open Research Experiments (ORE).
The components of this template include:

 - Your experiment created using the [jsPsych] library
 - A [robot participant](https://github.com/expfactory/expfactory-robots) to test the runtime of your experiment.
 - A [paper](paper) submission that describes your experiment.
 - A [continuous integration](.circleci/config.yml) workflow on CircleCI to do all of the above.
 - Pushing metadata and an experiment preview back to github pages.
 - A final deployment of your experiment to Docker Hub as a container.

To make all this happen, you just need to fork this repository, add your experiment and write the paper,
and then connect to Github, CircleCI, and Docker Hub. Let's get started!

## Step 1. Clone the Template

The first step is to clone the template. We advise you to 
[fork the repository](https://www.github.com/openbases/builder-jspsych) first 
(and then clone your fork). You can also just download the archive and then
add to version control on your own. Here is how to clone the repository:

```bash
git clone https://www.github.com/<username>/builder-jspsych
cd builder-jspsych
```

Notice that we have a jspsych task, it's in the folder [rt-task](rt-task),
and we derived it from the [jspsych tutorial](https://www.jspsych.org/tutorials/rt-task/).


**under construction**
