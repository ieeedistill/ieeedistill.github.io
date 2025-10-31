---
layout: page
permalink: /speakers/
title: Speakers
nav: true
nav_order: 2
---

## Invited Speakers

<br /><br />

<div class="team-container" style="display: flex; flex-direction: column; gap: 2rem;">

  <!-- Speaker: Saikat Chakraborty -->
  <div class="team-member" style="display: flex; align-items: flex-start; gap: 1rem;">
    <img
      src="{{ '/assets/img/speakers/saikat.png' | relative_url }}"
      alt="Saikat Chakraborty"
      style="width: 120px; height: 120px; object-fit: cover; border-radius: 50%; flex-shrink: 0;"
    />
    <div class="speaker-info" style="text-align: left;">
      <p style="margin: 0;"><strong>Dr. Saikat Chakraborty</strong></p>
      <p style="margin: 0 0 0.5rem;"><em>Senior Researcher, Microsoft</em></p>
      <p style="margin: 0;"><strong>Title:</strong> Proof Oriented Programming with AI : Towards trusted AI Assisted Programming </p>
      <p style="margin: 0;"><strong>Talk Abstract:</strong> AI can write code, but we don’t trust it—yet. Proof-oriented programming (PoP) changes the contract: developers write specifications, and code ships only when the proofs check. This talk argues for “PoP with AI”: a workflow where large language models draft programs and proofs, SMT-backed verifiers judge them, and retrieval/repair loops close the gap between intent and implementation. I’ll motivate the approach with concrete evidence from F*, Dafny, and Verus–style ecosystems and share results from our recent work that curates a large corpus of real, production-grade F* programs and proofs and uses it to train/evaluate LLMs. Fine-tuned (and cheaper) models, augmented with type-aware retrieval and verified by a program-fragment checker, can automatically synthesize a substantial fraction of definitions and lemmas—often matching or beating much larger models—while guaranteeing that only type-correct, solver-validated outputs survive. </p>
      <p style="margin: 0;"><strong>Bio:</strong> Dr. Saikat Chakraborty, a Senior Researcher in Microsoft Research’s RiSE group, works on reliability and trustworthiness in AI-powered programming tools. His focus spans reliable AI-generated code and AI-assisted formal programming.</p>
    </div>
  </div>
  
  <!-- Speaker: Dr. Sayem Mohammad Imtiaz -->
  <div class="team-member" style="display: flex; align-items: flex-start; gap: 1rem;">
    <img
      src="{{ '/assets/img/speakers/Sayem.jpg' | relative_url }}"
      alt="Dr. Sayem Mohammad Imtiaz"
      style="width: 120px; height: 120px; object-fit: cover; border-radius: 50%; flex-shrink: 0;"
    />
    <div class="speaker-info" style="text-align: left;">
      <p style="margin: 0;"><strong>Dr. Sayem Mohammad Imtiaz</strong></p>
      <p style="margin: 0 0 0.5rem;"><em>Research Scientist, Meta</em></p>
      <p style="margin: 0;"><strong>Title:</strong> Towards Safer Language Models: Tackling Inherited Issues?</p>
      <p style="margin: 0;"><strong>Talk Abstract: </strong> LLMs are not just another variant of neural networks — they show surprising abilities like in-context learning, instruction following, and reasoning, among others. This rightly caught the attention of both academia and industry, opening up a new wave of research aimed at understanding and improving them. One important direction is studying the biases LLMs inherit from their training data. Such biases can surface as hallucinations, toxicity, unethical behavior, or subjectivity. Another striking issue is their retention of copyrighted and sensitive information from the corpus. These problems create legal and moral dilemmas that limit where and how we can use LLMs. So what are we doing to fix these inherited issues? What risks do they actually pose? What challenges remain unsolved? I'll briefly touch on these critical topics that we need to address for safer LLM use. </p>
      <p style="margin: 0;"><strong>Bio:</strong> Dr. Imtiaz is a Research Scientist at Meta, developing ML-based brand safety solutions to protect advertisers’ reputations. His research spans in AI Engineering, model modularity, and error mitigation in large language models.</p>
    </div>
  </div>

  <!-- Speaker: Dr. Benjamin Steenhoek -->
  <div class="team-member" style="display: flex; align-items: flex-start; gap: 1rem;">
    <img
      src="{{ '/assets/img/speakers/ben.png' | relative_url }}"
      alt="Dr. Benjamin Steenhoek"
      style="width: 120px; height: 120px; object-fit: cover; border-radius: 50%; flex-shrink: 0;"
    />
    <div class="speaker-info" style="text-align: left;">
      <p style="margin: 0;"><strong>Dr. Benjamin Steenhoek</strong></p>
      <p style="margin: 0 0 0.5rem;"><em>Senior Researcher, Microsoft</em></p>
      <p style="margin: 0;"><strong>Title:</strong> From Secure Coding to Secure Coders: Trustworthy AI Partners in the Agent Era </p>
      <p style="margin: 0;"><strong>Talk Abstract:</strong> Coding agents have emerged as a new and transformative paradigm in software development, often granted free rein with the promise of making anyone a 10x developer. However, real-world "incidents" and research have shown that increased capabilities can lead to new foibles and vulnerabilities, making core security principles more critical than ever. To make agents effective, we must first establish them as trustworthy partners. In this talk, I will discuss several approaches to securing AI agents, highlighting the challenges of the shifting landscape of AI security and key insights for transforming agents into secure coders. </p>
      <p style="margin: 0;"><strong>Bio:</strong> Dr. Steenhoek works on making excellent developer tools for secure software engineering and developing next-generation agent systems for software engineering.</p>
    </div>
  </div>

  <!-- Speaker: Imtiaz Karim -->
  <div class="team-member" style="display: flex; align-items: flex-start; gap: 1rem;">
    <img
      src="{{ '/assets/img/speakers/imtiaz.jpg' | relative_url }}"
      alt="Saikat Chakraborty"
      style="width: 120px; height: 120px; object-fit: cover; border-radius: 50%; flex-shrink: 0;"
    />
    <div class="speaker-info" style="text-align: left;">
      <p style="margin: 0;"><strong>Dr. Imtiaz Karim</strong></p>
      <p style="margin: 0 0 0.5rem;"><em>Assistant Professor, University of Texas at Dallas</em></p>
      <p style="margin: 0;"><strong>Title:</strong> LLM and ML for Cellular Network Security: Challenges and Opportunities </p>
      <p style="margin: 0;"><strong>Talk Abstract:</strong> Cellular networks are the bedrock of modern communication. The recent deployment of 5G has generated further enthusiasm and opportunities in both academia and industry. Therefore, the security of cellular networks is critical. In this talk, I will elaborate on the essential challenges of ensuring cellular network security and move on to my research on using LLMs and ML to enhance the resilience of the networks. I will begin by discussing the analysis of 4G/5G specifications and introducing CellularLint, which uses a revamped few-shot learning mechanism on domain-adapted Large Language Models (LLMs) to detect inconsistencies in 4G and 5G specifications. Then, I will discuss an ML-based defensive approach, termed FBSDetector, which is devised to detect and defend against threats such as Fake Base Stations and multi-step attacks. I will conclude by outlining some of the challenges and opportunities of using LLMs and ML for ensuring the security and privacy of a highly specialized domain, such as 5G and NextG protocols and systems. </p>
      <p style="margin: 0;"><strong>Bio:</strong> Dr. Imtiaz Karim is an Assistant Professor of Computer Science at the University of Texas at Dallas, where he leads the System and Network Security (SysNetS) lab. His research focuses on securing wireless communication protocols and developing AI-driven tools to ensure the reliability and security of current and next-generation network systems. Prior to UTD, he was a Postdoctoral Researcher at Purdue University, where he also earned his Ph.D. in Computer Science.</p>
    </div>
  </div>
</div>
