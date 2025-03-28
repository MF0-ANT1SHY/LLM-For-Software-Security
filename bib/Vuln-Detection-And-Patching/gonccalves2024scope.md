@article{gonccalves2024scope,
  title={Scope: Evaluating llms for software vulnerability detection},
  author={Gon{\c{c}}alves, Jos{\'e} and Dias, Tiago and Maia, Eva and Pra{\c{c}}a, Isabel},
  journal={arXiv preprint arXiv:2407.14372},
  year={2024}
}


# Abstract:
In recent years, code security has become increasingly important, especially with the rise of interconnected technologies. Detecting vulnerabilities early in the software development process has demonstrated numerous benefits. Consequently, the scientific community started using machine learning for automated detection of source code vulnerabilities. This work explores and refines the CVEFixes dataset, which is commonly used to train models for code-related tasks, specifically the C/C++ subset. To this purpose, the Source Code Processing Engine (SCoPE), a framework composed of strategized techniques that can be used to reduce the size and normalize C/C++ functions is presented. The output generated by SCoPE was used to create a new version of CVEFixes. This refined dataset was then employed in a feature representation analysis to assess the effectiveness of the tool's code processing techniques, consisting of fine-tuning three pre-trained LLMs for software vulnerability detection. The results show that SCoPE successfully helped to identify 905 duplicates within the evaluated subset. The LLM results corroborate with the literature regarding their suitability for software vulnerability detection, with the best model achieving 53% F1-score.