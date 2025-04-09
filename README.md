# Research
Decoder/Temperature Inconsistency Analysis. Recreation of paper Figure 6, but vayring the settings of the model's decoder (here the temperature setting) instead of the level of difficulty of the problem. Analysis in the Figure stems from a G=10 (e.g., empirical sample of 10 trials per prompt) which is used to project model performance out to 100 repitions (i.e. varying r from 1 to 100). See the included .png image: GSM8K Dataset Reliablity Sets vs Temperature 0.0 to 2.0.png

Additionally Figure 1. is recreated using a problem from the MATH dataset.

Additional Citations used in our second reply to rebuttal by Reviewer tt4C

1. Jensen, B., Kwon, J. 2025. "The U.S. Army, Artificial Intelligence, and Mission Command" War On The Rocks. https://warontherocks.com/2025/03/the-u-s-army-artificial-intelligence-and-mission-command/ 
2. Chief of Staff, US Army. 2021. Army Multi-Domain Transformation Ready to Win in Competition and Conflict. https://api.army.mil/e2/c/downloads/2021/03/23/eeac3d01/20210319-csa-paper-1-signed-print-version.pdf
3. Young M, Smith MA. Standards and Evaluation of Healthcare Quality, Safety, and Person-Centered Care. 2025 Feb 24. In: StatPearls [Internet]. Treasure Island (FL): StatPearls Publishing; 2025 Jan–. PMID: 35015457. https://pubmed.ncbi.nlm.nih.gov/35015457/ 
4. Clusmann, J., Kolbinger, F.R., Muti, H.S. et al. The future landscape of large language models in medicine. Commun Med 3, 141 (2023). https://doi.org/10.1038/s43856-023-00370-1 https://www.nature.com/articles/s43856-023-00370-1#citeas

Additional Papers & Technical Reports that discuss using a plurality vote method to select the best answer along with the number of repitions they use:

1. Wang Et al. Use 20-40 votes. See page 4 and 8. https://arxiv.org/pdf/2203.11171

2. Lewkowycz et. al. show saturation at 16 & 64 votes, and use up to 256 votes. See page 2 and 8. https://arxiv.org/pdf/2206.14858

3. 2024 Gemini Technical report cites a Majority Vote of 32 (pages 8, 13, 25). https://arxiv.org/pdf/2312.11805

4. Model Car Claude 3 cites Majority Vote of 32 on MATH and several other data sets (See page 6). https://www-cdn.anthropic.com/de8ba9b01c9ab7cbabf5c33b80b7bbc618857627/Model_Card_Claude_3.pdf

5. Notably, the OpenAI GPT4 technical report makes no mention of a majority vote, or plurality vote of any kind. https://arxiv.org/pdf/2303.08774

Discussion of the inability to eliminate randomness in the decoder of OpenAI's models via the API:
This has been openly discussed on OpenAI’s Developer Community message board here: https://community.openai.com/t/clarifications-on-setting-temperature-0/886447 

Other citations:
Conformal Language Modeling by Quach, et al. https://arxiv.org/pdf/2306.10193
