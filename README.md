# Med42 - Clinical Large Language Model

**Our model is available at [Hugging Face](https://huggingface.co/m42-health/med42-70b)**

## Our Vision to Democratize Medical Knowledge with Med42

At M42, we recently unveiled Med42, our new open-access clinical large language model (LLM) designed to expand access to medical knowledge worldwide. With 70 billion parameters, this generative AI system provides high-quality answers to medical questions, achieving promising results on healthcare benchmarks.

Our motivation in developing Med42 was to create an AI assistant that could enhance clinical decision-making and increase access to an AI model for healthcare use. We envision Med42 powering diverse use cases, from creating useful summaries to aiding diagnoses and answering general health queries.

Central to our work is a steadfast commitment to rigorous testing and responsible research. By making Med42 open-source, our goal is to enable researchers globally to thoroughly evaluate it, providing feedback to improve the model and crucially understand its capabilities and limitations. Such collaborative assessment and transparency is essential to ensure the safe, ethical application of AI in the high-stakes healthcare domain.

We recognize further work needs to be done to enable Med42 for real-world clinical deployment. While initial benchmark results are encouraging, with Med42 outperforming proprietary models like ChatGPT 3.5 on medical exams, metrics alone are insufficient evidence of safety and efficacy. We are committed to performing extensive real-world evaluation across diverse clinical scenarios and patient populations.

By enabling access to Med42 through releasing it open-access, we seek to promote transparency, foster scientific collaboration, and accelerate innovation around developing better medical LLMs. With responsible research we believe we can together harness AI's potential to improve healthcare access and outcomes, while always prioritizing patient well-being. This is the principled path we are committed to, upholding rigorous ethics as Med42 progresses from the lab toward real-world testing.

The launch of Med42 is an exciting milestone, but improving this model further requires continued partnership. We don't have all the answers yet, which is why transparency and enabling access is so crucial. We warmly welcome researchers across disciplines to be part of this journey with us. Together through responsible collaboration, we can realize AI's potential to help clinicians better serve patients worldwide.

## Appendix: Performance comparison of Med42 with other LLMs

|Dataset|Med42|ClinicalCamel-70B|GPT-3.5|GPT-4.0|Med-PaLM-2 (5-shot)*|
|---|---|---|---|---|---|
|MMLU Clinical Knowledge|74.3|69.8|69.8|86.0|88.3|
|MMLU College Biology|84.0|79.2|72.2|95.1|94.4|
|MMLU College Medicine|68.8|67.0|61.3|76.9|80.9|
|MMLU Medical Genetics|86.0|69.0|70.0|91.0|90.0|
|MMLU Professional Medicine|79.8|71.3|70.2|93.0|95.2|
|MMLU Anatomy|67.4|62.2|56.3|80.0|77.8|
|MedMCQA|60.9|47.0|50.1|69.5|71.3|
|MedQA|61.5|53.4|50.8|78.9|79.7|
|USMLE Self-Assessment|71.7|-|49.1|83.8|-|
|USMLE Sample Exam|72.0|54.3|56.9|84.3|-|

Note:

- ClinicalCamel results are as reported by the authors ([link to paper](https://arxiv.org/abs/2305.12031))

- GPT-3.5 and GPT-4.0 are as reported by Nori et al. ([link to paper](https://arxiv.org/abs/2303.13375))

- Med-PaLM 2 results are as reported by the authors ([link to paper](https://arxiv.org/abs/2305.09617))

**We note that 0-shot performance is not reported for Med-PaLM 2*.
