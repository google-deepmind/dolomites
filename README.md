# DoLoMiTes: Domain-Specific Long-Form Methodical Tasks

This repository includes data for the DoLoMiTes (Domain-Specific Long-Form
Methodical Tasks) evaluation benchmark, described in [our paper](https://arxiv.org/abs/2405.05938).

## Abstract
  Experts in various fields routinely perform methodical writing tasks to plan, organize, and report their work. From a clinician writing a differential diagnosis for a patient, to a teacher writing a lesson plan for students, these tasks are pervasive, requiring to methodically generate structured long-form output for a given input. We develop a typology of methodical tasks structured in the form of a task objective, procedure, input, and output, and introduce DoLoMiTes, a novel benchmark with specifications for 519 such tasks elicited from hundreds of experts from across 25 fields. Our benchmark further contains specific instantiations of methodical tasks with concrete input and output examples (1,857 in total) which we obtain by collecting expert revisions of up to 10 model-generated examples of each task. We use these examples to evaluate contemporary language models highlighting that automating methodical tasks is a challenging long-form generation problem, as it requires performing complex inferences, while drawing upon the given context as well as domain knowledge.

## Data

The benchmark data is available in JSONL format at:
  * [Tasks](https://dolomites-benchmark.s3.us-west-2.amazonaws.com/dolomites_tasks_anon.jsonl): 519 task descriptions provided by experts.
  * [Tasks Validation Labels](https://dolomites-benchmark.s3.us-west-2.amazonaws.com/dolomites_tasks_validation.latest.website.jsonl): Labels for task validation provided by 3 independent experts.
  * [Examples](https://dolomites-benchmark.s3.us-west-2.amazonaws.com/dolomites_examples.zip): Examples of the tasks post-edited by experts. We provide the development set (830 examples) **with** reference outputs and the test set (1037 examples) **without** reference outputs.

## Citing this work

If you use any of the material here, please cite the following paper:

```latex
@article{malaviya2024dolomites,
  title={DOLOMITES: Domain-Specific Long-Form Methodical Tasks},
  author={Malaviya, Chaitanya and Agrawal, Priyanka and Ganchev, Kuzman and Srinivasan, Pranesh and Huot, Fantine and Berant, Jonathan and Yatskar, Mark and Das, Dipanjan and Lapata, Mirella and Alberti, Chris},
  journal={arXiv preprint arXiv:2405.05938},
  year={2024}
}
```

## License and disclaimer

Copyright 2024 DeepMind Technologies Limited

All software is licensed under the Apache License, Version 2.0 (Apache 2.0);
you may not use this file except in compliance with the Apache 2.0 license.
You may obtain a copy of the Apache 2.0 license at:
https://www.apache.org/licenses/LICENSE-2.0

All other materials are licensed under the Creative Commons Attribution 4.0
International License (CC-BY). You may obtain a copy of the CC-BY license at:
https://creativecommons.org/licenses/by/4.0/legalcode

Unless required by applicable law or agreed to in writing, all software and
materials distributed here under the Apache 2.0 or CC-BY licenses are
distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND,
either express or implied. See the licenses for the specific language governing
permissions and limitations under those licenses.

This is not an official Google product.
