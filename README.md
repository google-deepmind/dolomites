# DoLoMiTes: Domain-Specific Long-Form Methodical Tasks

This repository includes data for the DoLoMiTes (Domain-Specific Long-Form
Methodical Tasks) evaluation benchmark, described in [our paper](https://drive.google.com/file/d/1rQ6VEMbaS6L5DVJ1K-Le9OkJp1D2Rot3/view?usp=sharing&resourcekey=0-5O0KCfuDb1Kx_t7OMfsZJg) to be submitted to TACL 2024.

## Abstract
  Experts in various fields do methodical writing tasks in their profession to
  plan, organize and report their work. These tasks all require methodically
  generating a structured long-form output for a given input according to a
  task description. From a clinician writing a differential diagnosis for a
  patient, to a teacher writing a lesson plan for students, these tasks are
  pervasive across domains. In this work, we study the extent to which large
  language models can act as writing assistants for such domain-specific tasks.
  Our work introduces a novel benchmark called DoLoMiTes (Domain-Specific
  Long-Form Methodical Tasks) of more than 500 such domain-specific tasks
  (i.e. instructions) elicited from hundreds of experts from across 25 fields.
  These tasks represent real scenarios that experts tackle in various fields,
  formatted in the form of a task objective, procedure, input and output.
  Along with these tasks, we collect expert revisions of up to 10
  model-generated examples of each task. Our benchmark proposes a challenging
  long-form generation problem, as it requires performing complex inferences
  while drawing upon the given context as well as domain knowledge. We hope
  that the benchmark can be useful for evaluating models for long-form text
  generation in novel domain-specific scenarios.

## Data

The benchmark data is available in JSONL format at: [link](link-to-GCP-bucket-tbd).
This dataset contains 1857 examples split across 519 expert tasks.
Documents have an average length of 590 words.
Each example contains the following fields:
  * "field": the field of the expert executing the task, e.g. economics,
  * "task": instructions on how to perform the task, written by an expert,
  * "original example": LLM generated example for a task,
  * "edited example": original example revised by an expert in the field.

## Citing this work

If you use any of the material here, please cite the following paper:

```latex
@article{malaviya2024,
      title={DoLoMiTes: Domain-Specific Long-Form Methodical Tasks},
      author={Chaitanya Malaviya, Priyanka Agrawal, Kuzman Ganchev,
              Pranesh Srinivasan, Fantine Huot,Mirella Lapata, Jonathan Berant,
              Mark Yatskar, Chris Alberti},
      year={2024},
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
