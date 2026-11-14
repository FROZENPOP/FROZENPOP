# Hi, I'm Shreyas

I'm a CS student at UC Berkeley. I build iOS apps and machine learning projects, usually by picking something a little beyond me and figuring it out as I go.

The thing I'm most excited about right now is AI for science, especially computational biology.

## Projects

**[Chalkbook](https://github.com/FROZENPOP/chalkbook)**: a bouldering journal for iPhone. Log sessions, track projects, see your progress over time. It's live on the App Store ([link](https://apps.apple.com/us/app/chalkbook/id6831400511)). I built it to learn iOS development by actually shipping something. SwiftUI client, SwiftData model and migrations, a Supabase backend with row-level security, and test suites. The hardest part was keeping the local SwiftData store in sync with Supabase.

**[CRISPR guide RNA efficiency](https://github.com/FROZENPOP/CRISPR_TARGET_NN)**: CNN and GRU models in TensorFlow and Keras that predict a CRISPR-Cas9 guide RNA's on-target editing efficiency from its sequence, plus numerical features from public genomic datasets. I evaluated them against experimental data and Microsoft's Azimuth baseline. They didn't beat Azimuth (held-out MSE 0.0021 vs. 0.001245). A surprising amount of the work was just getting Azimuth, written in Python 2 on libraries that no longer exist, to run at all. This was an independent research project through Polygence, mentored by a researcher at Penn, and it's written up in a draft paper, *Investigating the Efficiency of Model-Based Approaches in Designing Guide RNAs for CRISPR*.

**[MedQuAD Bot](https://github.com/FROZENPOP/MEDQUAD_BOT)**: a medical Q&A chatbot I built end to end as a summer intern at SciEncephalon AI (2025). It embeds your question, searches a FAISS index of 15,426 question-answer pairs from NIH websites, and has an LLM write the answer from the closest matches. The hard part was getting answers supported by evidence instead of a plausible-sounding hallucination. It has no accuracy evaluation and no conversation memory. A learning project, not medical advice.

**Verbatim**: an inference acceleration layer for healthcare AI startups, built with my teammate Arnav in four days at SF Tech Week (October 2026). It drafts tokens from the session's existing context and checks them in one model pass, so summaries come out faster and identical to standard decoding. I did the benchmarks and evaluation, and the pitch and demo. In our prototype: up to 4.3x faster, with 36 of 36 outputs identical.

## Other things

- In high school I founded and coached a middle-school girls' ACSL team. They took 1st in the state.
- I cofounded my high school's AI club and taught lectures on machine learning.
- This semester: CS 61A, Data C8, Math 54.
- Stack: Python, Java, Swift, SwiftUI, SwiftData, TensorFlow, Keras, FAISS, Supabase, Streamlit, Git.

Outside of code I boulder, play piano and sketch. Lifetime goal: owning an ice cream shop.

[LinkedIn](https://www.linkedin.com/in/ssindhaval/) · shreyas.sindhaval@berkeley.edu
