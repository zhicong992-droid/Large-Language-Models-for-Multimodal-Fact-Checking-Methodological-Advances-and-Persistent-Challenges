# Fact-checking Dataset and SOTA Resources

A curated resource list for automated and multimodal fact-checking datasets and SOTA methods.

This README covers the first seven tables in the survey:

1. Claim Detection Datasets  
2. Claim Extraction Datasets  
3. Evidence Retrieval Datasets  
4. Out-of-context and Manipulation Detection Datasets  
5. Veracity Classification Datasets  
6. SOTA Results on Representative Fact-checking Datasets  
7. Justification Production Datasets  

> Verification policy:
> - We prioritize official project pages, official GitHub repositories, ACL Anthology, ACM Digital Library, AAAI/OJS, OpenReview, arXiv, NeurIPS Datasets & Benchmarks, FEVER official pages, Zenodo, Figshare, CodaLab, HuggingFace, and dataset owners' pages.
> - If no stable public data or code link was found, the entry is marked as `Not publicly available / no stable public link found`.
> - For some social-media, WhatsApp, short-video, and platform-restricted datasets, the paper may be public while raw data access is restricted.

---

# 1. Dataset Statistics

## 1.1 Claim Detection Datasets

| Category | Dataset | Year | Dataset Release Paper | Paper | Data |
|---|---:|---:|---|---|---|
| Claim Detection | CredBank | 2015 | CREDBANK: A Large-scale Social Media Corpus with Associated Credibility Annotations | [paper](https://ojs.aaai.org/index.php/ICWSM/article/view/14625) | [data](https://github.com/compsocial/CREDBANK-data) |
| Claim Detection | Weibo | 2016 | Detecting Rumors from Microblogs with Recurrent Neural Networks | [paper](https://www.ijcai.org/Proceedings/16/Papers/537.pdf) | [data](https://www.dropbox.com/s/46r50ctrfa0ur1o/rumdect.zip?dl=0) |
| Claim Detection | PHEME | 2016 | Analysing How People Orient to and Spread Rumours in Social Media by Looking at Conversational Threads | [paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0150989) | [data](https://figshare.com/articles/dataset/PHEME_rumour_scheme_dataset_journalism_use_case/2068650) |
| Claim Detection | RumourEval19 | 2019 | SemEval-2019 Task 7: RumourEval, Determining Rumour Veracity and Support for Rumours | [paper](https://aclanthology.org/S19-2147/) | [data](https://competitions.codalab.org/competitions/19938) |
| Claim Detection | DAST | 2019 | Joint Rumour Stance and Veracity Prediction | [paper](https://aclanthology.org/W19-6122/) | [data](https://huggingface.co/datasets/strombergnlp/dkstance) |
| Claim Detection | Suspicious | 2017 | Separating Facts from Fiction: Linguistic Models to Classify Suspicious and Trusted News Posts on Twitter | [paper](https://aclanthology.org/P17-2102/) | [data](https://aclanthology.org/attachments/P17-2102.Datasets.zip) |
| Claim Detection | CheckThat20-T1 | 2020 | Overview of CheckThat! 2020: Automatic Identification and Verification of Claims in Social Media | [paper](https://doi.org/10.1007/978-3-030-58219-7_17) | [data](https://sites.google.com/view/clef2020-checkthat/datasets-tools) |
| Claim Detection | CheckThat21-T1A | 2021 | The CLEF-2021 CheckThat! Lab on Detecting Check-Worthy Claims, Previously Fact-Checked Claims, and Fake News | [paper](https://doi.org/10.1007/978-3-030-72240-1_75) | [data](https://sites.google.com/view/clef2021-checkthat/tasks/task-1-check-worthiness-estimation) |
| Claim Detection | Debate | 2015 | Detecting Check-worthy Factual Claims in Presidential Debates | [paper](https://doi.org/10.1145/2806416.2806652) | Not publicly available / no stable public link found |
| Claim Detection | ClaimRank | 2017 | A Context-Aware Approach for Detecting Worth-Checking Claims in Political Debates | [paper](https://doi.org/10.26615/978-954-452-049-6_037) | [data/code](https://github.com/apepa/claim-rank) |
| Claim Detection | CheckThat18-T1 | 2018 | Overview of the CLEF-2018 CheckThat! Lab on Automatic Identification and Verification of Political Claims. Task 1: Check-Worthiness | [paper](https://ceur-ws.org/Vol-2125/invited_paper_13.pdf) | [data](https://github.com/clef2018-factchecking/clef2018-factchecking) |
| Claim Detection | CitationReason | 2019 | Citation Needed: A Taxonomy and Algorithmic Assessment of Wikipedia's Verifiability | [paper](https://doi.org/10.1145/3308558.3313618) | [data](https://figshare.com/articles/dataset/Citation_Reason_Dataset/7756226) |
| Claim Detection | PolitiTV | 2021 | Toward Automated Factchecking: Developing an Annotation Schema and Benchmark for Consistent Automated Claim Detection | [paper](https://doi.org/10.1145/3412869) | Not publicly available / no stable public link found |
| Claim Detection | BingCheck(raw) | 2024 | Self-Checker: Plug-and-Play Modules for Fact-Checking with Large Language Models | [paper](https://aclanthology.org/2024.findings-naacl.12/) | [data/code](https://github.com/Miaoranmmm/SelfChecker) |
| Claim Detection | IndiaWApp | 2020 | Images and Misinformation in Political Groups: Evidence from WhatsApp in India | [paper](https://arxiv.org/abs/2005.09784) | Not publicly available / no stable public link found |
| Claim Detection | DisinfoMeme | 2022 | DisinfoMeme: A Multimodal Dataset for Detecting Meme Intentionally Spreading Out Disinformation | [paper](https://arxiv.org/abs/2205.12617) | [data](https://github.com/uclanlp/DisinfoMeme) |
| Claim Detection | TikTok | 2021 | A Multimodal Misinformation Detector for COVID-19 Short Videos on TikTok | [paper](https://doi.org/10.1109/BigData52589.2021.9671928) | Not publicly available / no stable public link found |
| Claim Detection | COVID-VTS | 2023 | COVIDLies: Detecting COVID-19 Misinformation on Social Media | [paper](https://aclanthology.org/2020.nlpcovid19-2.11/) | [data](https://github.com/ucinlp/covid19-data) |
| Claim Detection | FakeSV | 2023 | FakeSV: A Multimodal Benchmark with Rich Social Context for Fake News Detection on Short Video Platforms | [paper](https://doi.org/10.1609/aaai.v37i12.26689) | [data](https://github.com/ICTMCG/FakeSV) |
| Claim Detection | WhatsApp Audio | 2021 | A Study of Misinformation in Audio Messages Shared in WhatsApp Groups | [paper](https://doi.org/10.1007/978-3-030-87031-7_6) | Not publicly available / no stable public link found |
| Claim Detection | Weibo Multimodal | 2017 | Multimodal Fusion with Recurrent Neural Networks for Rumor Detection on Microblogs | [paper](https://doi.org/10.1145/3123266.3123454) | [data](https://github.com/yaqingwang/EANN-KDD18) |
| Claim Detection | FauxBuster | 2018 | FauxBuster: A Content-free Fauxtography Detector Using Social Media Comments | [paper](https://doi.org/10.1109/BigData.2018.8622344) | Not publicly available / no stable public link found |
| Claim Detection | ExFaux | 2020 | ExFaux: A Weakly Supervised Approach to Explainable Fauxtography Detection | [paper](https://doi.org/10.1109/BigData50022.2020.9378019) | Not publicly available / no stable public link found |
| Claim Detection | MuMiN | 2022 | MuMiN: A Large-Scale Multilingual Multimodal Fact-Checked Misinformation Social Network Dataset | [paper](MuMiN: A Large-Scale Multilingual Multimodal Fact-Checked Misinformation Social Network Dataset) | [data](https://mumin-dataset.github.io/) |
| Claim Detection | MM-Claims | 2022 | MM-Claims: A Dataset for Multimodal Claim Detection in Social Media | [paper](https://aclanthology.org/2022.findings-naacl.72/) | [data](https://github.com/TIBHannover/MM_Claims) |
| Claim Detection | ContrastFaux | 2023 | ContrastFaux: Sparse Semi-supervised Fauxtography Detection on the Web using Multi-view Contrastive Learning | [paper](https://doi.org/10.1145/3543507.3583869) | Not publicly available / no stable public link found |
| Claim Detection | CLEF2023 | 2023 | The CLEF-2023 CheckThat! Lab: Checkworthiness, Subjectivity, Political Bias, Factuality, and Authority | [paper](https://doi.org/10.1007/978-3-031-28241-6_59) | [data](https://checkthat.gitlab.io/clef2023/) |
| Claim Detection | MR2 | 2023 | MR2: A Benchmark for Multimodal Retrieval-Augmented Rumor Detection in Social Media | [paper](https://doi.org/10.1145/3539618.3591896) | [data](https://github.com/THU-BPM/MR2) |
| Claim Detection | CheckMate | 2021 | Check Mate: Prioritizing User Generated Multi-Media Content for Fact-Checking | [paper](https://ojs.aaai.org/index.php/ICWSM/article/view/18126) | [data](https://zenodo.org/record/4032629) |
| Claim Detection | MisDissem | 2019 | (Mis)Information Dissemination in WhatsApp: Gathering, Analyzing and Countermeasures | [paper](https://doi.org/10.1145/3308558.3313688) | Not publicly available / no stable public link found |


---

## 1.2 Claim Extraction Datasets

| Category | Dataset | Year | Dataset Release Paper | Paper | Data |
|---|---:|---:|---|---|---|
| Claim Extraction | CURT | 2022 | Empowering the Fact-checkers! Automatic Identification of Claim Spans on Twitter | [paper](https://aclanthology.org/2022.emnlp-main.525/) | [data/code](https://github.com/LCS2-IIITD/DABERTA-EMNLP-2022) |
| Claim Extraction | X-CLAIM | 2023 | Lost in Translation, Found in Spans: Identifying Claims in Multilingual Social Media | [paper](https://aclanthology.org/2023.emnlp-main.236/) | [data](https://github.com/mbzuai-nlp/x-claim) |
| Claim Extraction | HECSI | 2024 | ICPR 2024 Competition on Multilingual Claim-Span Identification | [paper](https://doi.org/10.1007/978-3-031-80139-6_10) | [data](https://github.com/sohampoddar26/hecsi-data) |
| Claim Extraction | Multilingual-Claim-Span | 2025 | Enhancing Textual Understanding: Automated Claim Span Identification in English, Hindi, Bengali, and CodeMix | [paper](https://aclanthology.org/2025.ranlp-1.118/) | [data](https://github.com/pritampal98/claim-span-multilingual) |
| Claim Extraction | AVeriTeC-DCE | 2024 | Document-level Claim Extraction and Decontextualisation for Fact-Checking | [paper](https://aclanthology.org/2024.acl-long.645/) | [data](https://github.com/Tswings/AVeriTeC-DCE) |
| Claim Extraction | FEVERFact | 2025 | Claim Extraction for Fact-Checking: Data, Models, and Automated Metrics | [paper](https://arxiv.org/abs/2502.04955) | [data](https://github.com/aic-factcheck/claim_extraction) |
| Claim Extraction | CLAN | 2023 | From Chaos to Clarity: Claim Normalization to Empower Fact-Checking | [paper](https://aclanthology.org/2023.findings-emnlp.439/) | [data/code](https://github.com/LCS2-IIITD/CACN-EMNLP-2023) |
| Claim Extraction | mCLAN | 2025 | Overview of the CLEF-2025 CheckThat! Lab Task 2 on Claim Normalization | [paper](https://ceur-ws.org/Vol-4038/paper_52.pdf) | Not publicly available / no stable public link found |

---

## 1.3 Evidence Retrieval Datasets

| Category | Dataset | Year | Dataset Release Paper | Paper | Data |
|---|---:|---:|---|---|---|
| Evidence Retrieval | BEIR | 2021 | BEIR: A Heterogeneous Benchmark for Zero-shot Evaluation of Information Retrieval Models | [paper](https://arxiv.org/abs/2104.08663) | [data/code](https://github.com/beir-cellar/beir) |
| Evidence Retrieval | MS MARCO | 2016 | MS MARCO: A Human Generated MAchine Reading COmprehension Dataset | [paper](https://arxiv.org/abs/1611.09268) | [data](https://microsoft.github.io/msmarco/) |
| Evidence Retrieval | mMARCO | 2021 | mMARCO: A Multilingual Version of the MS MARCO Passage Ranking Dataset | [paper](https://arxiv.org/abs/2108.13897) | [data/code](https://github.com/unicamp-dl/mMARCO) |
| Evidence Retrieval | MIRACL | 2023 | MIRACL: A Multilingual Retrieval Dataset Covering 18 Diverse Languages | [paper](https://aclanthology.org/2023.tacl-1.63/) | [data](https://project-miracl.github.io/) |
| Evidence Retrieval | Mr. TyDi | 2021 | Mr. TyDi: A Multi-lingual Benchmark for Dense Retrieval | [paper](https://arxiv.org/abs/2108.08787) | [data/code](https://github.com/castorini/mr.tydi) |
| Evidence Retrieval | DuReader Retrieval | 2022 | DuReader Retrieval: A Large-scale Chinese Benchmark for Passage Retrieval | [paper](https://aclanthology.org/2022.emnlp-main.357/) | [data](https://github.com/baidu/DuReader/tree/master/DuReader-Retrieval) |
| Evidence Retrieval | BingCheck(full) | 2024 | Self-Checker: Plug-and-Play Modules for Fact-Checking with Large Language Models | [paper](https://aclanthology.org/2024.findings-naacl.12/) | [data/code](https://github.com/Miaoranmmm/SelfChecker) |
| Evidence Retrieval | WIT | 2021 | WIT: Wikipedia-based Image Text Dataset for Multimodal Multilingual Machine Learning | [paper](https://doi.org/10.1145/3404835.3463257) | [data](https://github.com/google-research-datasets/wit) |
| Evidence Retrieval | TRECVID | 2017 | Instance Search Retrospective with Focus on TRECVID | [paper](https://doi.org/10.1007/s13735-017-0121-3) | [data](https://trecvid.nist.gov/) |
| Evidence Retrieval | INRIA Holidays | 2008 | Hamming Embedding and Weak Geometric Consistency for Large Scale Image Search | [paper](https://doi.org/10.1007/978-3-540-88682-2_24) | [data](https://lear.inrialpes.fr/~jegou/data.php) |
| Evidence Retrieval | Stanford I2V | 2015 | Stanford I2V: A News Video Dataset for Query-by-Image Experiments | [paper](https://doi.org/10.1145/2713168.2713197) | [data](https://purl.stanford.edu/zx935qw7203) |
| Evidence Retrieval | NTU-VOI | 2016 | Object Instance Search in Videos via Spatio-Temporal Trajectory Discovery | [paper](https://cse.buffalo.edu/~jsyuan/papers/2016/Object%20Instance%20Search%20in%20Videos%20via%20Spatio-Temporal%20Trajectory%20Discovery.pdf) | [data](https://rose1.ntu.edu.sg/dataset/videoObjectInstance/) |
| Evidence Retrieval | FIVR-200K | 2019 | FIVR: Fine-grained Incident Video Retrieval | [paper](https://doi.org/10.1109/TMM.2019.2905741) | [data](https://ndd.iti.gr/fivr/) |
| Evidence Retrieval | VCDB | 2014 | VCDB: A Large-Scale Database for Partial Copy Detection in Videos | [paper](https://doi.org/10.1007/978-3-319-10593-2_24) | [data](https://fvl.fudan.edu.cn/dataset/vcdb/list.htm) |
| Evidence Retrieval | CC_WEB_VIDEO | 2009 | Large-scale Near-duplicate Web Video Search: Challenge and Opportunity | [paper](https://doi.org/10.1109/ICME.2009.5202830) | [data](https://www.ee.columbia.edu/ln/dvmm/downloads/CC_WEB_VIDEO/) |
| Evidence Retrieval | EVVE | 2013 | Event Retrieval in Large Video Collections with Circulant Temporal Encoding | [paper](https://openaccess.thecvf.com/content_cvpr_2013/html/Revaud_Event_Retrieval_in_2013_CVPR_paper.html) | [data](https://lear.inrialpes.fr/people/revaud/EVVE/) |

---

## 1.4 Out-of-context Detection Datasets

| Category | Dataset | Year | Dataset Release Paper | Paper | Data |
|---|---:|---:|---|---|---|
| Out-of-context | News400 | 2020 | Multimodal Analytics for Real-world News using Measures of Cross-modal Entity Consistency | [paper](https://doi.org/10.1145/3372278.3390670) | [data/code](https://github.com/TIBHannover/cross-modal_entity_consistency) |
| Out-of-context | Ookpik | 2024 | Ookpik: A Collection of Out-of-Context Image-Caption Pairs | [paper](https://doi.org/10.1007/978-3-031-53302-0_10) | Not publicly available / no stable public link found |
| Out-of-context | InfoSurgeon | 2021 | InfoSurgeon: Cross-Media Fine-grained Information Consistency Checking for Fake News Detection | [paper](https://aclanthology.org/2021.acl-long.133/) | [data/code](https://github.com/yrf1/InfoSurgeon) |
| Out-of-context | TNews | 2020 | Multimodal Analytics for Real-world News using Measures of Cross-modal Entity Consistency | [paper](https://doi.org/10.1145/3372278.3390670) | [data/code](https://github.com/TIBHannover/cross-modal_entity_consistency) |
| Out-of-context | NeuralNews | 2020 | Detecting Cross-Modal Inconsistency to Defend Against Neural Fake News | [paper](https://aclanthology.org/2020.emnlp-main.163/) | [data/code](https://github.com/rxtan2/DIDAN) |
| Out-of-context | MEIR | 2018 | Deep Multimodal Image-Repurposing Detection | [paper](https://arxiv.org/abs/1808.06686) | [data/code](https://github.com/Ekraam/MEIR) |
| Out-of-context | COSMOS | 2023 | COSMOS: Catching Out-of-Context Image Misuse Using Self-Supervised Learning | [paper](https://ojs.aaai.org/index.php/AAAI/article/view/26648) | [data/code](https://github.com/shivangi-aneja/COSMOS) |
| Out-of-context | MAIM | 2017 | Multimedia Semantic Integrity Assessment Using Joint Embedding Of Images And Text | [paper](https://doi.org/10.1145/3123266.3123385) | Not publicly available / no stable public link found |
| Out-of-context | Twitter-COMMs | 2022 | Twitter-COMMs: Detecting Climate, COVID, and Military Multimodal Misinformation | [paper](https://aclanthology.org/2022.naacl-main.110/) | [data/code](https://github.com/GiscardBiamby/Twitter-COMMs) |
| Out-of-context | NewsCLIPings | 2021 | NewsCLIPpings: Automatic Generation of Out-of-Context Multimodal Media | [paper](https://arxiv.org/abs/2104.05893) | [data/code](https://github.com/g-luo/news_clippings) |
| Out-of-context | MMOOC | 2024 | MMOOC: A Multimodal Misinformation Dataset for Out-of-Context News Analysis | [paper](https://doi.org/10.1007/978-981-97-5101-3_24) | Not publicly available / no stable public link found |

---

## 1.5 Manipulation Detection Datasets

| Category | Dataset | Year | Dataset Release Paper | Paper | Data |
|---|---:|---:|---|---|---|
| Manipulation Detection | In-the-Wild | 2018 | Fighting Fake News: Image Splice Detection via Learned Self-Consistency | [paper](https://openaccess.thecvf.com/content_ECCV_2018/html/Jacob_Huh_Fighting_Fake_News_ECCV_2018_paper.html) | [data/code](https://github.com/minyoungg/selfconsistency) |
| Manipulation Detection | MediaEval | 2014 | Challenges of Computational Verification in Social Multimedia | [paper](https://doi.org/10.1145/2567948.2579323) | [data](https://github.com/MKLab-ITI/image-verification-corpus) |
| Manipulation Detection | FakingSandy | 2013 | Faking Sandy: Characterizing and Identifying Fake Images on Twitter during Hurricane Sandy | [paper](https://doi.org/10.1145/2487788.2488033) | [data](https://github.com/MKLab-ITI/image-verification-corpus) |
| Manipulation Detection | PS-Battles | 2018 | PS-Battles: A Dataset for Image Manipulation Detection | [paper](https://arxiv.org/abs/1804.04866) | [data](https://github.com/dbisUnibas/PS-Battles) |
| Manipulation Detection | DGM | 2023 | Detecting and Grounding Multi-Modal Media Manipulation | [paper](https://openaccess.thecvf.com/content/CVPR2023/html/Shao_Detecting_and_Grounding_Multi-Modal_Media_Manipulation_CVPR_2023_paper.html) | [data/code](https://github.com/rshaojimmy/MultiModal-DeepFake) |
| Manipulation Detection | SID-Set | 2025 | SIDA: Social Media Image Deepfake Detection, Localization and Explanation with Large Multimodal Model | [paper](https://openaccess.thecvf.com/content/CVPR2025/html/Huang_SIDA_Social_Media_Image_Deepfake_Detection_Localization_and_Explanation_with_CVPR_2025_paper.html) | [data/code](https://github.com/hzlsaber/SIDA) |
| Manipulation Detection | GenImage | 2023 | GenImage: A Million-Scale Benchmark for Detecting AI-Generated Image | [paper](https://arxiv.org/abs/2306.08571) | [data](https://github.com/GenImage-Dataset/GenImage) |
| Manipulation Detection | VTD | 2016 | Development of a Video Tampering Dataset for Forensic Investigation | [paper](https://doi.org/10.1016/j.forsciint.2016.07.026) | [data](https://www.kaggle.com/datasets/neetusingla5/video-forgery-dataset) |
| Manipulation Detection | DeepfakeDetect | 2018 | Deepfake Video Detection Using Recurrent Neural Networks | [paper](https://ieeexplore.ieee.org/document/8639163) | Not publicly available / no stable public link found |
| Manipulation Detection | FaceForensics | 2018 | FaceForensics: A Large-scale Video Dataset for Forgery Detection in Human Faces | [paper](https://arxiv.org/abs/1803.09179) | [data](https://justusthies.github.io/posts/faceforensics/) |
| Manipulation Detection | Celeb-DF | 2020 | Celeb-DF: A Large-scale Challenging Dataset for DeepFake Forensics | [paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Li_Celeb-DF_A_Large-Scale_Challenging_Dataset_for_DeepFake_Forensics_CVPR_2020_paper.html) | [data](https://github.com/yuezunli/celeb-deepfakeforensics) |
| Manipulation Detection | DeeperForensics-1.0 | 2020 | DeeperForensics-1.0: A Large-Scale Dataset for Real-World Face Forgery Detection | [paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Jiang_DeeperForensics-1.0_A_Large-Scale_Dataset_for_Real-World_Face_Forgery_Detection_CVPR_2020_paper.html) | [data](https://github.com/EndlessSora/DeeperForensics-1.0) |
| Manipulation Detection | DFDC | 2020 | The DeepFake Detection Challenge Dataset | [paper](https://arxiv.org/abs/2006.07397) | [data](https://ai.meta.com/datasets/dfdc/) |
| Manipulation Detection | DF-Platter | 2023 | DF-Platter: Multi-Face Heterogeneous Deepfake Dataset | [paper](https://arxiv.org/abs/2303.09228) | [data](https://iab-rubric.org/df-platter-database) |
| Manipulation Detection | KoDF | 2021 | KoDF: A Large-scale Korean DeepFake Detection Dataset | [paper](https://openaccess.thecvf.com/content/ICCV2021/html/Kwon_KoDF_A_Large-Scale_Korean_DeepFake_Detection_Dataset_ICCV_2021_paper.html) | [data](https://moneybrain-research.github.io/kodf/) |
| Manipulation Detection | ASVspoof | 2015 | ASVspoof 2015: The First Automatic Speaker Verification Spoofing and Countermeasures Challenge | [paper](https://www.isca-archive.org/interspeech_2015/wu15e_interspeech.html) | [data](https://www.asvspoof.org/index2015.html) |
| Manipulation Detection | DeepSonar | 2020 | DeepSonar: Towards Effective and Robust Detection of AI-Synthesized Fake Voices | [paper](https://doi.org/10.1145/3394171.3413716) | Not publicly available / no stable public link found |
| Manipulation Detection | ADFF 2024 | 2025 | Generalized Audio Deepfake Detection Using Frame-level Latent Information Entropy | [paper](https://arxiv.org/abs/2504.10819) | Not publicly available / no stable public link found |
| Manipulation Detection | Phonespoof | 2019 | Phonespoof: A New Dataset for Spoofing Attack Detection in Telephone Channel | [paper](https://doi.org/10.1109/ICASSP.2019.8682942) | Not publicly available / no stable public link found |
| Manipulation Detection | FoR | 2019 | FoR: A Dataset for Synthetic Speech Detection | [paper](https://ieeexplore.ieee.org/document/8906599) | [data](https://bil.eecs.yorku.ca/datasets/) |
| Manipulation Detection | HAD | 2021 | Half-Truth: A Partially Fake Audio Detection Dataset | [paper](https://doi.org/10.21437/Interspeech.2021-930) | [data](https://github.com/HelloHAD/HAD) |
| Manipulation Detection | ASVspoof 5 | 2024 | ASVspoof 5: Crowdsourced Speech Deepfake Detection | [paper](https://arxiv.org/abs/2408.08739) | [data](https://www.asvspoof.org/) |
| Manipulation Detection | Deepfake-Eval-2024 | 2025 | Deepfake-Eval-2024: A Multi-Modal In-the-Wild Deepfake Benchmark | [paper](https://arxiv.org/abs/2503.02857) | [data](https://github.com/truemediaorg/socialbot.) |
| Manipulation Detection | FakeAVCeleb | 2021 | FakeAVCeleb: A Novel Audio-Video Multimodal Deepfake Dataset | [paper](https://neurips.cc/virtual/2021/29888) | [data](https://github.com/DASH-Lab/FakeAVCeleb) |
| Manipulation Detection | AV-Deepfake1M | 2024 | AV-Deepfake1M: A Large-Scale LLM-Driven Audio-Visual Deepfake Dataset | [paper](https://doi.org/10.1145/3664647.3680795) | [data](https://github.com/ControlNet/AV-Deepfake1M) |

---

## 1.6 Veracity Classification Datasets

| Category | Dataset | Year | Dataset Release Paper | Paper | Data |
|---|---:|---:|---|---|---|
| Veracity Classification | FEVER | 2018 | FEVER: a Large-scale Dataset for Fact Extraction and VERification | [paper](https://aclanthology.org/N18-1074/) | [data](https://fever.ai/resources.html) |
| Veracity Classification | LIAR | 2017 | "Liar, Liar Pants on Fire": A New Benchmark Dataset for Fake News Detection | [paper](https://aclanthology.org/P17-2067/) | [data](https://sites.cs.ucsb.edu/~william/software.html) |
| Veracity Classification | FEVEROUS | 2021 | FEVEROUS: Fact Extraction and VERification Over Unstructured and Structured Information | [paper](https://arxiv.org/abs/2106.05707) | [data](https://fever.ai/dataset/feverous.html) |
| Veracity Classification | VitaminC | 2021 | Get Your Vitamin C! Robust Fact Verification with Contrastive Evidence | [paper](https://aclanthology.org/2021.naacl-main.52/) | [data/code](https://github.com/TalSchuster/VitaminC) |
| Veracity Classification | HoVer | 2020 | HoVer: A Dataset for Many-Hop Fact Extraction And Claim Verification | [paper](https://aclanthology.org/2020.findings-emnlp.309/) | [data](https://hover-nlp.github.io/) |
| Veracity Classification | AVeriTeC | 2023 | AVeriTeC: A Dataset for Real-world Claim Verification with Evidence from the Web | [paper](https://arxiv.org/abs/2305.13117) | [data/code](https://github.com/MichSchli/AVeriTeC) |
| Veracity Classification | X-FACT | 2021 | X-FACT: A New Benchmark Dataset for Multilingual Fact Checking | [paper](https://aclanthology.org/2021.acl-short.86/) | [data/code](https://github.com/utahnlp/x-fact) |
| Veracity Classification | LIAR2 | 2024 | An Enhanced Fake News Detection System with Fuzzy Deep Learning | [paper](https://doi.org/10.1109/ACCESS.2024.3418340) | [data](https://github.com/chengxuphd/liar2) |
| Veracity Classification | CFEVER | 2024 | CFEVER: A Chinese Fact Extraction and VERification Dataset | [paper](https://doi.org/10.1609/aaai.v38i17.29825) | [data](https://github.com/IKMLab/CFEVER-data) |
| Veracity Classification | CREAK | 2021 | CREAK: A Dataset for Commonsense Reasoning over Entity Knowledge | [paper](https://neurips.cc/virtual/2021/29907) | [data/code](https://github.com/yasumasaonoe/creak) |
| Veracity Classification | FaVIQ | 2022 | FaVIQ: FAct Verification from Information-seeking Questions | [paper](https://aclanthology.org/2022.acl-long.354/) | [data](https://faviq.github.io/) |
| Veracity Classification | DanFEVER | 2021 | DanFEVER: Claim Verification Dataset for Danish | [paper](https://aclanthology.org/2021.nodalida-main.47/) | [data](https://figshare.com/articles/dataset/DanFEVER_claim_verification_dataset_for_Danish/14380970) |
| Veracity Classification | CoVERT | 2022 | CoVERT: A Corpus of Fact-checked Biomedical COVID-19 Tweets | [paper](https://aclanthology.org/2022.lrec-1.26/) | [data](https://www.ims.uni-stuttgart.de/en/research/resources/corpora/bioclaim/) |
| Veracity Classification | Stanceosaurus | 2022 | Stanceosaurus: Classifying Stance Towards Multilingual Misinformation | [paper](https://aclanthology.org/2022.emnlp-main.138/) | [data/code](https://github.com/JonathanQZheng/Stanceosaurus) |
| Veracity Classification | SciFact | 2020 | Fact or Fiction: Verifying Scientific Claims | [paper](https://aclanthology.org/2020.emnlp-main.609/) | [data/code](https://github.com/allenai/scifact) |
| Veracity Classification | TabFact | 2020 | TabFact: A Large-scale Dataset for Table-based Fact Verification | [paper](https://iclr.cc/virtual_2020/poster_rkeJRhNYDH.html) | [data/code](https://github.com/wenhuchen/Table-Fact-Checking) |
| Veracity Classification | WatClaimCheck | 2022 | WatClaimCheck: A New Dataset for Claim Entailment and Inference | [paper](https://aclanthology.org/2022.acl-long.92/) | [data/code](https://github.com/nxii/WatClaimCheck) |
| Veracity Classification | WikiFactCheck | 2020 | Automated Fact-Checking of Claims from Wikipedia | [paper](https://aclanthology.org/2020.lrec-1.849/) | [data/code](https://github.com/wikifactcheck-english/wikifactcheck-english) |
| Veracity Classification | CHEF | 2022 | CHEF: A Pilot Chinese Dataset for Evidence-Based Fact-Checking | [paper](https://aclanthology.org/2022.naacl-main.246/) | [data/code](https://github.com/THU-BPM/CHEF) |
| Veracity Classification | ChatGPT-FC | 2023 | A Revisit of Fake News Dataset with Augmented Fact-checking by ChatGPT | [paper](https://arxiv.org/abs/2312.11870) | Not publicly available / no stable public link found |
| Veracity Classification | MultiFC | 2019 | MultiFC: A Real-World Multi-Domain Dataset for Evidence-Based Fact Checking of Claims | [paper](https://aclanthology.org/D19-1475/) | [data](https://competitions.codalab.org/competitions/21163) |
| Veracity Classification | FakeNewsNet | 2020 | FakeNewsNet: A Data Repository with News Content, Social Context and Spatiotemporal Information for Studying Fake News on Social Media | [paper](https://doi.org/10.1089/big.2020.0062) | [data/code](https://github.com/KaiDMML/FakeNewsNet) |
| Veracity Classification | MultiClaim | 2023 | Multilingual Previously Fact-Checked Claim Retrieval | [paper](https://aclanthology.org/2023.emnlp-main.1027/) | [data](https://zenodo.org/records/7737983) |
| Veracity Classification | BingCheck | 2024 | Self-Checker: Plug-and-Play Modules for Fact-Checking with Large Language Models | [paper](https://aclanthology.org/2024.findings-naacl.12/) | [data/code](https://github.com/Miaoranmmm/SelfChecker) |
| Veracity Classification | MOCHEG | 2023 | End-to-End Multimodal Fact-Checking and Explanation Generation: A Challenging Dataset and Models | [paper](https://doi.org/10.1145/3539618.3591879) | [data/code](https://github.com/VT-NLP/Mocheg) |
| Veracity Classification | VERITE | 2024 | VERITE: A Robust Benchmark for Multimodal Misinformation Detection Accounting for Unimodal Bias | [paper](https://doi.org/10.1007/s13735-023-00312-6) | [data/code](https://github.com/stevejpapad/image-text-verification) |
| Veracity Classification | Factify | 2022 | FACTIFY: A Multi-Modal Fact Verification Dataset | [paper](https://ceur-ws.org/Vol-3199/paper18.pdf) | [data](https://codalab.lisn.upsaclay.fr/competitions/8275) |
| Veracity Classification | Factify 2 | 2023 | Factify 2: A Multimodal Fake News and Satire News Dataset | [paper](https://arxiv.org/abs/2304.03897) | [data/code](https://github.com/surya1701/Factify-2.0) |
| Veracity Classification | MM-Claims | 2022 | MM-Claims: A Dataset for Multimodal Claim Detection in Social Media | [paper](https://aclanthology.org/2022.findings-naacl.72/) | [data/code](https://github.com/TIBHannover/MM_Claims) |
| Veracity Classification | STVD-FC | 2022 | A Large-scale TV Video and Metadata Database for French Political Content Analysis and Fact-checking | [paper](https://doi.org/10.1145/3549555.3549557) | [data](http://mathieu.delalandre.free.fr/projects/stvd/fc/) |
| Veracity Classification | FakeSV | 2023 | FakeSV: A Multimodal Benchmark with Rich Social Context for Fake News Detection on Short Video Platforms | [paper](https://doi.org/10.1609/aaai.v37i12.26689) | [data/code](https://github.com/ICTMCG/FakeSV) |
| Veracity Classification | FakeTT | 2024 | FakingRecipe: Detecting Fake News on Short Video Platforms from the Perspective of Creative Process | [paper](https://doi.org/10.1145/3664647.3680663) | [data/code](https://github.com/ICTMCG/FakingRecipe) |
| Veracity Classification | FakeVV | 2025 | Fact-R1: Towards Explainable Video Misinformation Detection with Deep Reasoning | [paper](https://arxiv.org/abs/2505.16836) | [data/code](https://github.com/zfr00/fact-r1) |
| Veracity Classification | CheckMate | 2021 | Check Mate: Prioritizing User Generated Multi-Media Content for Fact-Checking | [paper](https://ojs.aaai.org/index.php/ICWSM/article/view/18126) |[data](https://zenodo.org/record/4032629) |
| Veracity Classification | TRUE | 2025 | Pioneering Explainable Video Fact-Checking with a New Dataset and Multi-role Multimodal Model Approach | [paper](https://ojs.aaai.org/index.php/AAAI/article/view/35048) | [data/code](https://github.com/MeiTaylor/TRUE) |

---

## 1.7 Justification Production Datasets

| Category | Dataset | Year | Dataset Release Paper | Paper | Data |
|---|---:|---:|---|---|---|
| Justification Production | FEVER | 2018 | FEVER: a Large-scale Dataset for Fact Extraction and VERification | [paper](https://aclanthology.org/N18-1074/) | [data](https://fever.ai/resources.html) |
| Justification Production | HoVer | 2020 | HoVer: A Dataset for Many-Hop Fact Extraction And Claim Verification | [paper](https://aclanthology.org/2020.findings-emnlp.309/) | [data](https://hover-nlp.github.io/) |
| Justification Production | SciFact | 2020 | Fact or Fiction: Verifying Scientific Claims | [paper](https://aclanthology.org/2020.emnlp-main.609/) | [data/code](https://github.com/allenai/scifact) |
| Justification Production | ExClaim | 2024 | JustiLM: Few-shot Justification Generation for Explainable Fact-Checking of Real-world Claims | [paper](https://aclanthology.org/2024.tacl-1.19/) | [data/code](https://github.com/znhy1024/JustiLM) |
| Justification Production | FactEx | 2023 | Generative AI for Explainable Automated Fact Checking on the FactEx: A New Benchmark Dataset | [paper](https://doi.org/10.1007/978-3-031-47896-3_1) | Not publicly available / no stable public link found |
| Justification Production | LIAR-PLUS | 2018 | Where is Your Evidence: Improving Fact-checking by Justification Modeling | [paper](https://aclanthology.org/W18-5513/) | [data/code](https://github.com/Tariq60/LIAR-PLUS) |
| Justification Production | LIAR++ | 2023 | Benchmarking the Generation of Fact Checking Explanations | [paper](https://aclanthology.org/2023.tacl-1.71/) | [data/code](https://github.com/LanD-FBK/benchmark-gen-explanations) |
| Justification Production | FullFact | 2023 | Benchmarking the Generation of Fact Checking Explanations | [paper](https://aclanthology.org/2023.tacl-1.71/) | [data/code](https://github.com/LanD-FBK/benchmark-gen-explanations) |
| Justification Production | PUBHEALTH | 2020 | Explainable Automated Fact-Checking for Public Health Claims | [paper](https://aclanthology.org/2020.emnlp-main.623/) | [data/code](https://github.com/neemakot/Health-Fact-Checking) |
| Justification Production | AVeriTeC | 2023 | AVeriTeC: A Dataset for Real-world Claim Verification with Evidence from the Web | [paper](https://arxiv.org/abs/2305.13117) | [data/code](https://github.com/MichSchli/AVeriTeC) |
| Justification Production | EX-FEVER | 2024 | EX-FEVER: A Dataset for Multi-hop Explainable Fact Verification | [paper](https://aclanthology.org/2024.findings-acl.556/) | [data/code](https://github.com/dependentsign/EX-FEVER) |
| Justification Production | e-FEVER | 2020 | e-FEVER: Explanations and Summaries for Automated Fact Checking | [paper](https://truthandtrustonline.com/wp-content/uploads/2020/10/TTO04.pdf) | Not publicly available / no stable public link found |
| Justification Production | FlawCheck | 2024 | How We Refute Claims: Automatic Fact-Checking through Flaw Identification and Explanation | [paper](https://arxiv.org/abs/2401.15312) | [data/code](https://github.com/NYCU-NLP-Lab/FlawCheck) |
| Justification Production | FEVEROUS | 2021 | FEVEROUS: Fact Extraction and VERification Over Unstructured and Structured Information | [paper](https://arxiv.org/abs/2106.05707) | [data](https://fever.ai/dataset/feverous.html) |
| Justification Production | ChartCheck | 2024 | ChartCheck: Explainable Fact-Checking over Real-World Chart Images | [paper](https://aclanthology.org/2024.findings-acl.828/) | [data/code](https://github.com/mubasharaak/ChartCheck) |
| Justification Production | MOCHEG | 2023 | End-to-End Multimodal Fact-Checking and Explanation Generation: A Challenging Dataset and Models | [paper](https://doi.org/10.1145/3539618.3591879) | [data/code](https://github.com/VT-NLP/Mocheg) |
| Justification Production | RW-Post | 2025 | Auditable Evidence-Grounded Multimodal Fact-Checking in the Wild | [paper](https://arxiv.org/abs/2512.22933) | [data](https://github.com/xudanni0927/AgentFact) |
| Justification Production | TRUE-ECR | 2025 | Pioneering Explainable Video Fact-Checking with a New Dataset and Multi-role Multimodal Model Approach | [paper](https://ojs.aaai.org/index.php/AAAI/article/view/35048) | [data/code](https://github.com/MeiTaylor/TRUE) |
| Justification Production | TRUE-LSR | 2025 | Pioneering Explainable Video Fact-Checking with a New Dataset and Multi-role Multimodal Model Approach | [paper](https://ojs.aaai.org/index.php/AAAI/article/view/35048) | [data/code](https://github.com/MeiTaylor/TRUE) |
| Justification Production | MMM-Fact | 2025 | MMM-Fact: A Multimodal, Multi-Domain Fact-Checking Dataset with Multi-Level Retrieval Difficulty | [paper](https://arxiv.org/abs/2510.25120) | [data](https://huggingface.co/datasets/Wenyan0110/MMM-Fact) |

---

# 2. SOTA Statistics

| SOTA Dataset | SOTA Method | Year | SOTA Paper | Paper | Code |
|---|---|---:|---|---|---|
| FEVER | CorXFact | 2025 | Improving Explainable Fact-Checking with Claim-Evidence Correlation | [paper](https://aclanthology.org/2025.coling-main.108/) | [code](https://github.com/txAnnie/Explainable-Fact-checking) |
| LIAR | Fake Detect | 2021 | Fake Detect: A Deep Learning Ensemble Model for Fake News Detection | [paper](https://doi.org/10.1155/2021/5557784) | Not found / not publicly released |
| FEVEROUS | Varnosfaderani et al. | 2024 | Bridging Textual and Tabular Worlds for Fact Verification: A Lightweight, Attention-Based Model | [paper](https://aclanthology.org/2024.lrec-main.226/) | [code](https://github.com/nii-yamagishilab/MLA-FEVEROUS-COLING24) |
| VitaminC | VitaminC | 2021 | Get Your Vitamin C! Robust Fact Verification with Contrastive Evidence | [paper](https://aclanthology.org/2021.naacl-main.52/) | [code](https://github.com/TalSchuster/VitaminC) |
| HoVer | MRR-FV | 2025 | MRR-FV: Unlocking Complex Fact Verification with Multi-Hop Retrieval and Reasoning | [paper](https://ojs.aaai.org/index.php/AAAI/article/view/34802) | Not found / not publicly released |
| AVeriTeC | HerO | 2024 | HerO at AVeriTeC: The Herd of Open Large Language Models for Verifying Real-World Claims | [paper](https://aclanthology.org/2024.fever-1.15/) | [code](https://github.com/ssu-humane/HerO) |
| X-FACT | Singhal et al. | 2024 | Multilingual Fact-Checking Using LLMs | [paper](https://aclanthology.org/2024.nlp4pi-1.2/) | Not found / not publicly released |
| LIAR2 | FDHN | 2024 | An Enhanced Fake News Detection System with Fuzzy Deep Learning | [paper](https://doi.org/10.1109/ACCESS.2024.3418340) | [code](https://github.com/chengxuphd/FDHN) |
| CFEVER | Lin et al. | 2024 | CFEVER: A Chinese Fact Extraction and VERification Dataset | [paper](https://doi.org/10.1609/aaai.v38i17.29825) | [code/data](https://github.com/IKMLab/CFEVER-data) |
| CREAK | Onoe et al. | 2021 | CREAK: A Dataset for Commonsense Reasoning over Entity Knowledge | [paper](https://neurips.cc/virtual/2021/29907) | [code/data](https://github.com/yasumasaonoe/creak) |
| FaVIQ | QaDialMoE | 2022 | QaDialMoE: Question-answering Dialogue based Fact Verification with Mixture of Experts | [paper](https://aclanthology.org/2022.findings-emnlp.229/) | [code](https://github.com/wishever/QaDialMoE) |
| DanFEVER | Nørregaard et al. | 2021 | DanFEVER: Claim Verification Dataset for Danish | [paper](https://aclanthology.org/2021.nodalida-main.47/) | Not found / not publicly released |
| CoVERT | CliVER | 2024 | Retrieval Augmented Scientific Claim Verification | [paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC10919922/) | Not found / not publicly released |
| Stanceosaurus | Zheng et al. | 2022 | Stanceosaurus: Classifying Stance Towards Multilingual Misinformation | [paper](https://aclanthology.org/2022.emnlp-main.138/) | [code](https://github.com/JonathanQZheng/Stanceosaurus) |
| SciFact | Fine-tuned NLI Models | 2024 | Scientific Claim Verification with Fine-Tuned NLI Models | [paper](https://doi.org/10.5220/0012900000003838) | Not found / not publicly released |
| TabFact | ARTEMIS-DA | 2025 | ARTEMIS-DA: An Advanced Reasoning and Transformation Engine for Multi-Step Insight Synthesis in Data Analytics | [paper](https://arxiv.org/abs/2412.14146) | Not found / not publicly released |
| WikiFactCheck | Sathe et al. | 2020 | Automated Fact-Checking of Claims from Wikipedia | [paper](https://aclanthology.org/2020.lrec-1.849/) | [code/data](https://github.com/wikifactcheck-english/wikifactcheck-english) |
| CHEF | Hu et al. | 2022 | CHEF: A Pilot Chinese Dataset for Evidence-Based Fact-Checking | [paper](https://aclanthology.org/2022.naacl-main.246/) | [code/data](https://github.com/THU-BPM/CHEF) |
| MultiFC | DRIVE | 2025 | DRIVE: An Adjustable Parallel Architecture Based on Evidence Awareness for Fake News Detection | [paper](https://doi.org/10.1016/j.eswa.2024.126043) | Not found / not publicly released |
| FakeNewsNet | Saja et al. | 2022 | Fake News Detection Using Machine Learning and Deep Learning | [paper](https://www.sciencedirect.com/org/science/article/pii/S1546221823006380) | Not found / not publicly released |
| BingCheck | Self-Checker | 2024 | Self-Checker: Plug-and-Play Modules for Fact-Checking with Large Language Models | [paper](https://aclanthology.org/2024.findings-naacl.12/) | [code](https://github.com/Miaoranmmm/SelfChecker) |
| MOCHEG | DEFAME | 2024 | Dynamic Evidence-based FAct-checking with Multimodal Experts | [paper](https://arxiv.org/abs/2412.10510) | [code](https://github.com/multimodal-ai-lab/DEFAME) |
| VERITE | DEFAME | 2024 | Dynamic Evidence-based FAct-checking with Multimodal Experts | [paper](https://arxiv.org/abs/2412.10510) | [code](https://github.com/multimodal-ai-lab/DEFAME) |
| Factify | UofA-Truth / Dhankar et al. | 2022 | UofA-Truth at Factify 2022: A Simple Approach to Multi-Modal Fact-Checking | [paper](https://ceur-ws.org/Vol-3199/paper10.pdf) | Not found / not publicly released |
| Factify 2 | Suryavardan et al. | 2023 | Factify 2: A Multimodal Fake News and Satire News Dataset | [paper](https://arxiv.org/abs/2304.03897) | [code/data](https://github.com/surya1701/Factify-2.0) |
| MM-Claims | Cheema et al. | 2022 | MM-Claims: A Dataset for Multimodal Claim Detection in Social Media | [paper](https://aclanthology.org/2022.findings-naacl.72/) | [code/data](https://github.com/TIBHannover/MM_Claims) |
| FakeSV | Fact-R1 | 2025 | Fact-R1: Towards Explainable Video Misinformation Detection with Deep Reasoning | [paper](https://arxiv.org/abs/2505.16836) | [code](https://github.com/zfr00/fact-r1) |
| FakeTT | Fact-R1 | 2025 | Fact-R1: Towards Explainable Video Misinformation Detection with Deep Reasoning | [paper](https://arxiv.org/abs/2505.16836) | [code](https://github.com/zfr00/fact-r1) |
| FakeVV | Fact-R1 | 2025 | Fact-R1: Towards Explainable Video Misinformation Detection with Deep Reasoning | [paper](https://arxiv.org/abs/2505.16836) | [code](https://github.com/zfr00/fact-r1) |
| TRUE | Niu et al. | 2025 | Pioneering Explainable Video Fact-Checking with a New Dataset and Multi-role Multimodal Model Approach | [paper](https://ojs.aaai.org/index.php/AAAI/article/view/35048) | [code/data](https://github.com/MeiTaylor/TRUE) |

---

# 3. Citation Policy

When using any dataset or method from this list, please cite:

1. The dataset release paper.
2. The method paper or SOTA system paper, if using reported model results.
3. The official repository or data-hosting platform when required by its license.

