# AI with VD Academy

**AI Engineering Course.** 20 phases, 523 lessons, 373 quizzes. From your first dev environment to agents, protocols and production systems.

Read the lessons and take the quizzes on https://aiwithvd.com/academy. This repo holds the code and the take-away files for every lesson.

## Where to start

| Your background | Start at |
|---|---|
| New to programming and AI | [Phase 0: Setup & Tooling](phases/00-setup-and-tooling) |
| You know Python, new to ML | [Phase 1: Math Foundations](phases/01-math-foundations) |
| You know ML, new to deep learning | [Phase 3: Deep Learning Core](phases/03-deep-learning-core) |
| You know deep learning, want LLMs and agents | [Phase 10: LLMs from Scratch](phases/10-llms-from-scratch) |
| You only want agent engineering | [Phase 14: Agent Engineering](phases/14-agent-engineering) |

## How a lesson works

1. Read the lesson on https://aiwithvd.com/academy.
2. Run the code in `phases/<phase>/<lesson>/code/`.
3. Keep the take-away files in `phases/<phase>/<lesson>/outputs/`: skills and prompts you can reuse in your own work.

## Run the code

```bash
git clone https://github.com/aiwithvd/ai-engineering.git
cd ai-engineering
python3 -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
```

Some lessons use TypeScript, Julia or Rust. Each lesson says which languages it needs.

## Curriculum

### Phase 0: Setup & Tooling

Get your environment ready for everything that follows.

| # | Lesson | Type | Time | Files |
|---|---|---|---|---|
| 01 | Dev Environment | Build | ~45 minutes | [code](phases/00-setup-and-tooling/01-dev-environment/code) · [take-away files](phases/00-setup-and-tooling/01-dev-environment/outputs) |
| 02 | Git & Collaboration | Learn | ~30 minutes | - |
| 03 | GPU Setup & Cloud | Build | ~45 minutes | [code](phases/00-setup-and-tooling/03-gpu-setup-and-cloud/code) |
| 04 | APIs & Keys | Build | ~30 minutes | [code](phases/00-setup-and-tooling/04-apis-and-keys/code) · [take-away files](phases/00-setup-and-tooling/04-apis-and-keys/outputs) |
| 05 | Jupyter Notebooks | Build | ~30 minutes | [code](phases/00-setup-and-tooling/05-jupyter-notebooks/code) · [take-away files](phases/00-setup-and-tooling/05-jupyter-notebooks/outputs) |
| 06 | Python Environments | Build | ~30 minutes | [code](phases/00-setup-and-tooling/06-python-environments/code) |
| 07 | Docker for AI | Build | ~60 minutes | [code](phases/00-setup-and-tooling/07-docker-for-ai/code) |
| 08 | Editor Setup | Build | ~20 minutes | [code](phases/00-setup-and-tooling/08-editor-setup/code) |
| 09 | Data Management | Build | ~45 minutes | [code](phases/00-setup-and-tooling/09-data-management/code) · [take-away files](phases/00-setup-and-tooling/09-data-management/outputs) |
| 10 | Terminal & Shell | Learn | ~35 minutes | [code](phases/00-setup-and-tooling/10-terminal-and-shell/code) |
| 11 | Linux for AI | Learn | ~30 minutes | - |
| 12 | Debugging and Profiling | Build | ~60 minutes | [code](phases/00-setup-and-tooling/12-debugging-and-profiling/code) · [take-away files](phases/00-setup-and-tooling/12-debugging-and-profiling/outputs) |

### Phase 1: Math Foundations

The intuition behind every AI algorithm, through code.

| # | Lesson | Type | Time | Files |
|---|---|---|---|---|
| 01 | Linear Algebra Intuition | Learn | ~60 minutes | [code](phases/01-math-foundations/01-linear-algebra-intuition/code) · [take-away files](phases/01-math-foundations/01-linear-algebra-intuition/outputs) |
| 02 | Vectors, Matrices & Operations | Build | ~60 minutes | [code](phases/01-math-foundations/02-vectors-matrices-operations/code) · [take-away files](phases/01-math-foundations/02-vectors-matrices-operations/outputs) |
| 03 | Matrix Transformations | Build | ~75 minutes | [code](phases/01-math-foundations/03-matrix-transformations/code) · [take-away files](phases/01-math-foundations/03-matrix-transformations/outputs) |
| 04 | Calculus for Machine Learning | Learn | ~60 minutes | [code](phases/01-math-foundations/04-calculus-for-ml/code) · [take-away files](phases/01-math-foundations/04-calculus-for-ml/outputs) |
| 05 | Chain Rule & Automatic Differentiation | Build | ~90 minutes | [code](phases/01-math-foundations/05-chain-rule-and-autodiff/code) · [take-away files](phases/01-math-foundations/05-chain-rule-and-autodiff/outputs) |
| 06 | Probability and Distributions | Learn | ~75 minutes | [code](phases/01-math-foundations/06-probability-and-distributions/code) · [take-away files](phases/01-math-foundations/06-probability-and-distributions/outputs) |
| 07 | Bayes' Theorem | Build | ~75 minutes | [code](phases/01-math-foundations/07-bayes-theorem/code) · [take-away files](phases/01-math-foundations/07-bayes-theorem/outputs) |
| 08 | Optimization | Build | ~75 minutes | [code](phases/01-math-foundations/08-optimization/code) · [take-away files](phases/01-math-foundations/08-optimization/outputs) |
| 09 | Information Theory | Learn | ~60 minutes | [code](phases/01-math-foundations/09-information-theory/code) · [take-away files](phases/01-math-foundations/09-information-theory/outputs) |
| 10 | Dimensionality Reduction | Build | ~90 minutes | [code](phases/01-math-foundations/10-dimensionality-reduction/code) · [take-away files](phases/01-math-foundations/10-dimensionality-reduction/outputs) |
| 11 | Singular Value Decomposition | Build | ~120 minutes | [code](phases/01-math-foundations/11-singular-value-decomposition/code) · [take-away files](phases/01-math-foundations/11-singular-value-decomposition/outputs) |
| 12 | Tensor Operations | Build | ~90 minutes | [code](phases/01-math-foundations/12-tensor-operations/code) · [take-away files](phases/01-math-foundations/12-tensor-operations/outputs) |
| 13 | Numerical Stability | Build | ~120 minutes | [code](phases/01-math-foundations/13-numerical-stability/code) · [take-away files](phases/01-math-foundations/13-numerical-stability/outputs) |
| 14 | Norms and Distances | Build | ~90 minutes | [code](phases/01-math-foundations/14-norms-and-distances/code) · [take-away files](phases/01-math-foundations/14-norms-and-distances/outputs) |
| 15 | Statistics for Machine Learning | Build | ~120 minutes | [code](phases/01-math-foundations/15-statistics-for-ml/code) · [take-away files](phases/01-math-foundations/15-statistics-for-ml/outputs) |
| 16 | Sampling Methods | Build | ~120 minutes | [code](phases/01-math-foundations/16-sampling-methods/code) · [take-away files](phases/01-math-foundations/16-sampling-methods/outputs) |
| 17 | Linear Systems | Build | ~120 minutes | [code](phases/01-math-foundations/17-linear-systems/code) · [take-away files](phases/01-math-foundations/17-linear-systems/outputs) |
| 18 | Convex Optimization | Build | ~90 minutes | [code](phases/01-math-foundations/18-convex-optimization/code) · [take-away files](phases/01-math-foundations/18-convex-optimization/outputs) |
| 19 | Complex Numbers for AI | Learn | ~60 minutes | [code](phases/01-math-foundations/19-complex-numbers/code) · [take-away files](phases/01-math-foundations/19-complex-numbers/outputs) |
| 20 | The Fourier Transform | Build | ~90 minutes | [code](phases/01-math-foundations/20-fourier-transform/code) · [take-away files](phases/01-math-foundations/20-fourier-transform/outputs) |
| 21 | Graph Theory for Machine Learning | Build | ~90 minutes | [code](phases/01-math-foundations/21-graph-theory/code) · [take-away files](phases/01-math-foundations/21-graph-theory/outputs) |
| 22 | Stochastic Processes | Learn | ~75 minutes | [code](phases/01-math-foundations/22-stochastic-processes/code) · [take-away files](phases/01-math-foundations/22-stochastic-processes/outputs) |

### Phase 2: ML Fundamentals

Classical ML, still the backbone of most production AI.

| # | Lesson | Type | Time | Files |
|---|---|---|---|---|
| 01 | What Is Machine Learning | Learn | ~45 minutes | [code](phases/02-ml-fundamentals/01-what-is-machine-learning/code) · [take-away files](phases/02-ml-fundamentals/01-what-is-machine-learning/outputs) |
| 02 | Linear Regression | Build | ~90 minutes | [code](phases/02-ml-fundamentals/02-linear-regression/code) · [take-away files](phases/02-ml-fundamentals/02-linear-regression/outputs) |
| 03 | Logistic Regression | Build | ~90 minutes | [code](phases/02-ml-fundamentals/03-logistic-regression/code) · [take-away files](phases/02-ml-fundamentals/03-logistic-regression/outputs) |
| 04 | Decision Trees and Random Forests | Build | ~90 minutes | [code](phases/02-ml-fundamentals/04-decision-trees/code) · [take-away files](phases/02-ml-fundamentals/04-decision-trees/outputs) |
| 05 | Support Vector Machines | Build | ~90 minutes | [code](phases/02-ml-fundamentals/05-support-vector-machines/code) · [take-away files](phases/02-ml-fundamentals/05-support-vector-machines/outputs) |
| 06 | K-Nearest Neighbors and Distances | Build | ~90 minutes | [code](phases/02-ml-fundamentals/06-knn-and-distances/code) · [take-away files](phases/02-ml-fundamentals/06-knn-and-distances/outputs) |
| 07 | Unsupervised Learning | Build | ~90 minutes | [code](phases/02-ml-fundamentals/07-unsupervised-learning/code) · [take-away files](phases/02-ml-fundamentals/07-unsupervised-learning/outputs) |
| 08 | Feature Engineering & Selection | Build | ~90 minutes | [code](phases/02-ml-fundamentals/08-feature-engineering/code) · [take-away files](phases/02-ml-fundamentals/08-feature-engineering/outputs) |
| 09 | Model Evaluation | Build | ~90 minutes | [code](phases/02-ml-fundamentals/09-model-evaluation/code) · [take-away files](phases/02-ml-fundamentals/09-model-evaluation/outputs) |
| 10 | Bias-Variance Tradeoff | Learn | ~75 minutes | [code](phases/02-ml-fundamentals/10-bias-variance/code) · [take-away files](phases/02-ml-fundamentals/10-bias-variance/outputs) |
| 11 | Ensemble Methods | Build | ~120 minutes | [code](phases/02-ml-fundamentals/11-ensemble-methods/code) · [take-away files](phases/02-ml-fundamentals/11-ensemble-methods/outputs) |
| 12 | Hyperparameter Tuning | Build | ~90 minutes | [code](phases/02-ml-fundamentals/12-hyperparameter-tuning/code) · [take-away files](phases/02-ml-fundamentals/12-hyperparameter-tuning/outputs) |
| 13 | ML Pipelines | Build | ~120 minutes | [code](phases/02-ml-fundamentals/13-ml-pipelines/code) · [take-away files](phases/02-ml-fundamentals/13-ml-pipelines/outputs) |
| 14 | Naive Bayes | Build | ~75 minutes | [code](phases/02-ml-fundamentals/14-naive-bayes/code) · [take-away files](phases/02-ml-fundamentals/14-naive-bayes/outputs) |
| 15 | Time Series Fundamentals | Build | ~90 minutes | [code](phases/02-ml-fundamentals/15-time-series/code) · [take-away files](phases/02-ml-fundamentals/15-time-series/outputs) |
| 16 | Anomaly Detection | Build | ~75 minutes | [code](phases/02-ml-fundamentals/16-anomaly-detection/code) · [take-away files](phases/02-ml-fundamentals/16-anomaly-detection/outputs) |
| 17 | Handling Imbalanced Data | Build | ~90 minutes | [code](phases/02-ml-fundamentals/17-imbalanced-data/code) · [take-away files](phases/02-ml-fundamentals/17-imbalanced-data/outputs) |
| 18 | Feature Selection | Build | ~75 minutes | [code](phases/02-ml-fundamentals/18-feature-selection/code) · [take-away files](phases/02-ml-fundamentals/18-feature-selection/outputs) |

### Phase 3: Deep Learning Core

Neural networks from first principles. No frameworks until you build one.

| # | Lesson | Type | Time | Files |
|---|---|---|---|---|
| 01 | The Perceptron | Build | ~60 minutes | [code](phases/03-deep-learning-core/01-the-perceptron/code) · [take-away files](phases/03-deep-learning-core/01-the-perceptron/outputs) |
| 02 | Multi-Layer Networks and Forward Pass | Build | ~90 minutes | [code](phases/03-deep-learning-core/02-multi-layer-networks/code) · [take-away files](phases/03-deep-learning-core/02-multi-layer-networks/outputs) |
| 03 | Backpropagation from Scratch | Build | ~120 minutes | [code](phases/03-deep-learning-core/03-backpropagation/code) · [take-away files](phases/03-deep-learning-core/03-backpropagation/outputs) |
| 04 | Activation Functions | Build | ~75 minutes | [code](phases/03-deep-learning-core/04-activation-functions/code) · [take-away files](phases/03-deep-learning-core/04-activation-functions/outputs) |
| 05 | Loss Functions | Build | ~75 minutes | [code](phases/03-deep-learning-core/05-loss-functions/code) · [take-away files](phases/03-deep-learning-core/05-loss-functions/outputs) |
| 06 | Optimizers | Build | ~75 minutes | [code](phases/03-deep-learning-core/06-optimizers/code) · [take-away files](phases/03-deep-learning-core/06-optimizers/outputs) |
| 07 | Regularization | Build | ~75 minutes | [code](phases/03-deep-learning-core/07-regularization/code) · [take-away files](phases/03-deep-learning-core/07-regularization/outputs) |
| 08 | Weight Initialization and Training Stability | Build | ~90 minutes | [code](phases/03-deep-learning-core/08-weight-initialization/code) · [take-away files](phases/03-deep-learning-core/08-weight-initialization/outputs) |
| 09 | Learning Rate Schedules and Warmup | Build | ~90 minutes | [code](phases/03-deep-learning-core/09-learning-rate-schedules/code) · [take-away files](phases/03-deep-learning-core/09-learning-rate-schedules/outputs) |
| 10 | Build Your Own Mini Framework | Build | ~120 minutes | [code](phases/03-deep-learning-core/10-mini-framework/code) · [take-away files](phases/03-deep-learning-core/10-mini-framework/outputs) |
| 11 | Introduction to PyTorch | Build | ~75 minutes | [code](phases/03-deep-learning-core/11-intro-to-pytorch/code) · [take-away files](phases/03-deep-learning-core/11-intro-to-pytorch/outputs) |
| 12 | Introduction to JAX | Build | ~90 minutes | [code](phases/03-deep-learning-core/12-intro-to-jax/code) · [take-away files](phases/03-deep-learning-core/12-intro-to-jax/outputs) |
| 13 | Debugging Neural Networks | Build | ~90 minutes | [code](phases/03-deep-learning-core/13-debugging-neural-networks/code) · [take-away files](phases/03-deep-learning-core/13-debugging-neural-networks/outputs) |

### Phase 4: Computer Vision

From pixels to understanding, image, video, 3D, VLMs, and world models.

| # | Lesson | Type | Time | Files |
|---|---|---|---|---|
| 01 | Image Fundamentals, Pixels, Channels, Color Spaces | Build | ~45 minutes | [code](phases/04-computer-vision/01-image-fundamentals/code) · [take-away files](phases/04-computer-vision/01-image-fundamentals/outputs) |
| 02 | Convolutions from Scratch | Build | ~75 minutes | [code](phases/04-computer-vision/02-convolutions-from-scratch/code) · [take-away files](phases/04-computer-vision/02-convolutions-from-scratch/outputs) |
| 03 | CNNs, LeNet to ResNet | Learn + Build | ~75 minutes | [code](phases/04-computer-vision/03-cnns-lenet-to-resnet/code) · [take-away files](phases/04-computer-vision/03-cnns-lenet-to-resnet/outputs) |
| 04 | Image Classification | Build | ~75 minutes | [code](phases/04-computer-vision/04-image-classification/code) · [take-away files](phases/04-computer-vision/04-image-classification/outputs) |
| 05 | Transfer Learning & Fine-Tuning | Build | ~75 minutes | [code](phases/04-computer-vision/05-transfer-learning/code) · [take-away files](phases/04-computer-vision/05-transfer-learning/outputs) |
| 06 | Object Detection, YOLO from Scratch | Build | ~75 minutes | [code](phases/04-computer-vision/06-object-detection-yolo/code) · [take-away files](phases/04-computer-vision/06-object-detection-yolo/outputs) |
| 07 | Semantic Segmentation, U-Net | Build | ~75 minutes | [code](phases/04-computer-vision/07-semantic-segmentation-unet/code) · [take-away files](phases/04-computer-vision/07-semantic-segmentation-unet/outputs) |
| 08 | Instance Segmentation, Mask R-CNN | Build + Learn | ~75 minutes | [code](phases/04-computer-vision/08-instance-segmentation-mask-rcnn/code) · [take-away files](phases/04-computer-vision/08-instance-segmentation-mask-rcnn/outputs) |
| 09 | Image Generation, GANs | Build | ~75 minutes | [code](phases/04-computer-vision/09-image-generation-gans/code) · [take-away files](phases/04-computer-vision/09-image-generation-gans/outputs) |
| 10 | Image Generation, Diffusion Models | Build | ~75 minutes | [code](phases/04-computer-vision/10-image-generation-diffusion/code) · [take-away files](phases/04-computer-vision/10-image-generation-diffusion/outputs) |
| 11 | Stable Diffusion, Architecture & Fine-Tuning | Learn + Use | ~75 minutes | [code](phases/04-computer-vision/11-stable-diffusion/code) · [take-away files](phases/04-computer-vision/11-stable-diffusion/outputs) |
| 12 | Video Understanding, Temporal Modeling | Learn + Build | ~45 minutes | [code](phases/04-computer-vision/12-video-understanding/code) · [take-away files](phases/04-computer-vision/12-video-understanding/outputs) |
| 13 | 3D Vision, Point Clouds & NeRFs | Learn + Build | ~45 minutes | [code](phases/04-computer-vision/13-3d-vision-nerf/code) · [take-away files](phases/04-computer-vision/13-3d-vision-nerf/outputs) |
| 14 | Vision Transformers (ViT) | Build | ~45 minutes | [code](phases/04-computer-vision/14-vision-transformers/code) · [take-away files](phases/04-computer-vision/14-vision-transformers/outputs) |
| 15 | Real-Time Vision, Edge Deployment | Learn + Build | ~75 minutes | [code](phases/04-computer-vision/15-real-time-edge/code) · [take-away files](phases/04-computer-vision/15-real-time-edge/outputs) |
| 16 | Build a Complete Vision Pipeline, Capstone | Build | ~120 minutes | [code](phases/04-computer-vision/16-vision-pipeline-capstone/code) · [take-away files](phases/04-computer-vision/16-vision-pipeline-capstone/outputs) |
| 17 | Self-Supervised Vision, SimCLR, DINO, MAE | Learn + Build | ~75 minutes | [code](phases/04-computer-vision/17-self-supervised-vision/code) · [take-away files](phases/04-computer-vision/17-self-supervised-vision/outputs) |
| 18 | Open-Vocabulary Vision, CLIP | Build + Use | ~45 minutes | [code](phases/04-computer-vision/18-open-vocab-clip/code) · [take-away files](phases/04-computer-vision/18-open-vocab-clip/outputs) |
| 19 | OCR & Document Understanding | Learn + Use | ~45 minutes | [code](phases/04-computer-vision/19-ocr-document-understanding/code) · [take-away files](phases/04-computer-vision/19-ocr-document-understanding/outputs) |
| 20 | Image Retrieval & Metric Learning | Build | ~45 minutes | [code](phases/04-computer-vision/20-image-retrieval-metric/code) · [take-away files](phases/04-computer-vision/20-image-retrieval-metric/outputs) |
| 21 | Keypoint Detection & Pose Estimation | Build | ~45 minutes | [code](phases/04-computer-vision/21-keypoint-pose/code) · [take-away files](phases/04-computer-vision/21-keypoint-pose/outputs) |
| 22 | 3D Gaussian Splatting from Scratch | Build | ~90 minutes | [code](phases/04-computer-vision/22-3d-gaussian-splatting/code) · [take-away files](phases/04-computer-vision/22-3d-gaussian-splatting/outputs) |
| 23 | Diffusion Transformers & Rectified Flow | Learn + Build | ~75 minutes | [code](phases/04-computer-vision/23-diffusion-transformers-rectified-flow/code) · [take-away files](phases/04-computer-vision/23-diffusion-transformers-rectified-flow/outputs) |
| 24 | SAM 3 & Open-Vocabulary Segmentation | Use + Build | ~60 minutes | [code](phases/04-computer-vision/24-sam3-open-vocab-segmentation/code) · [take-away files](phases/04-computer-vision/24-sam3-open-vocab-segmentation/outputs) |
| 25 | Vision-Language Models, The ViT-MLP-LLM Pattern | Learn + Use | ~75 minutes | [code](phases/04-computer-vision/25-vision-language-models/code) · [take-away files](phases/04-computer-vision/25-vision-language-models/outputs) |
| 26 | Monocular Depth & Geometry Estimation | Build + Use | ~60 minutes | [code](phases/04-computer-vision/26-monocular-depth/code) · [take-away files](phases/04-computer-vision/26-monocular-depth/outputs) |
| 27 | Multi-Object Tracking & Video Memory | Build | ~60 minutes | [code](phases/04-computer-vision/27-multi-object-tracking/code) · [take-away files](phases/04-computer-vision/27-multi-object-tracking/outputs) |
| 28 | World Models & Video Diffusion | Learn + Build | ~75 minutes | [code](phases/04-computer-vision/28-world-models-video-diffusion/code) · [take-away files](phases/04-computer-vision/28-world-models-video-diffusion/outputs) |

### Phase 5: NLP: Foundations to Advanced

Language is the interface to intelligence.

| # | Lesson | Type | Time | Files |
|---|---|---|---|---|
| 01 | Text Processing, Tokenization, Stemming, Lemmatization | Build | ~45 minutes | [code](phases/05-nlp-foundations-to-advanced/01-text-processing/code) · [take-away files](phases/05-nlp-foundations-to-advanced/01-text-processing/outputs) |
| 02 | Bag of Words, TF-IDF, and Text Representation | Build | ~75 minutes | [code](phases/05-nlp-foundations-to-advanced/02-bag-of-words-tfidf/code) · [take-away files](phases/05-nlp-foundations-to-advanced/02-bag-of-words-tfidf/outputs) |
| 03 | Word Embeddings, Word2Vec from Scratch | Build | ~75 minutes | [code](phases/05-nlp-foundations-to-advanced/03-word-embeddings-word2vec/code) · [take-away files](phases/05-nlp-foundations-to-advanced/03-word-embeddings-word2vec/outputs) |
| 04 | GloVe, FastText, and Subword Embeddings | Build | ~45 minutes | [code](phases/05-nlp-foundations-to-advanced/04-glove-fasttext-subword/code) · [take-away files](phases/05-nlp-foundations-to-advanced/04-glove-fasttext-subword/outputs) |
| 05 | Sentiment Analysis | Build | ~75 minutes | [code](phases/05-nlp-foundations-to-advanced/05-sentiment-analysis/code) · [take-away files](phases/05-nlp-foundations-to-advanced/05-sentiment-analysis/outputs) |
| 06 | Named Entity Recognition | Build | ~75 minutes | [code](phases/05-nlp-foundations-to-advanced/06-named-entity-recognition/code) · [take-away files](phases/05-nlp-foundations-to-advanced/06-named-entity-recognition/outputs) |
| 07 | POS Tagging and Syntactic Parsing | Build | ~45 minutes | [code](phases/05-nlp-foundations-to-advanced/07-pos-tagging-parsing/code) · [take-away files](phases/05-nlp-foundations-to-advanced/07-pos-tagging-parsing/outputs) |
| 08 | CNNs and RNNs for Text | Build | ~75 minutes | [code](phases/05-nlp-foundations-to-advanced/08-cnns-rnns-for-text/code) · [take-away files](phases/05-nlp-foundations-to-advanced/08-cnns-rnns-for-text/outputs) |
| 09 | Sequence-to-Sequence Models | Build | ~75 minutes | [code](phases/05-nlp-foundations-to-advanced/09-sequence-to-sequence/code) · [take-away files](phases/05-nlp-foundations-to-advanced/09-sequence-to-sequence/outputs) |
| 10 | Attention Mechanism, The Breakthrough | Build | ~45 minutes | [code](phases/05-nlp-foundations-to-advanced/10-attention-mechanism/code) · [take-away files](phases/05-nlp-foundations-to-advanced/10-attention-mechanism/outputs) |
| 11 | Machine Translation | Build | ~75 minutes | [code](phases/05-nlp-foundations-to-advanced/11-machine-translation/code) · [take-away files](phases/05-nlp-foundations-to-advanced/11-machine-translation/outputs) |
| 12 | Text Summarization | Build | ~75 minutes | [code](phases/05-nlp-foundations-to-advanced/12-text-summarization/code) · [take-away files](phases/05-nlp-foundations-to-advanced/12-text-summarization/outputs) |
| 13 | Question Answering Systems | Build | ~75 minutes | [code](phases/05-nlp-foundations-to-advanced/13-question-answering/code) · [take-away files](phases/05-nlp-foundations-to-advanced/13-question-answering/outputs) |
| 14 | Information Retrieval and Search | Build | ~75 minutes | [code](phases/05-nlp-foundations-to-advanced/14-information-retrieval-search/code) · [take-away files](phases/05-nlp-foundations-to-advanced/14-information-retrieval-search/outputs) |
| 15 | Topic Modeling, LDA and BERTopic | Learn | ~45 minutes | [code](phases/05-nlp-foundations-to-advanced/15-topic-modeling/code) · [take-away files](phases/05-nlp-foundations-to-advanced/15-topic-modeling/outputs) |
| 16 | Text Generation Before Transformers, N-gram Language Models | Build | ~45 minutes | [code](phases/05-nlp-foundations-to-advanced/16-text-generation-pre-transformer/code) · [take-away files](phases/05-nlp-foundations-to-advanced/16-text-generation-pre-transformer/outputs) |
| 17 | Chatbots, Rule-Based to Neural to LLM Agents | Learn | ~75 minutes | [code](phases/05-nlp-foundations-to-advanced/17-chatbots-rule-to-neural/code) · [take-away files](phases/05-nlp-foundations-to-advanced/17-chatbots-rule-to-neural/outputs) |
| 18 | Multilingual NLP | Learn | ~45 minutes | [code](phases/05-nlp-foundations-to-advanced/18-multilingual-nlp/code) · [take-away files](phases/05-nlp-foundations-to-advanced/18-multilingual-nlp/outputs) |
| 19 | Subword Tokenization, BPE, WordPiece, Unigram, SentencePiece | Learn | ~60 minutes | [code](phases/05-nlp-foundations-to-advanced/19-subword-tokenization/code) · [take-away files](phases/05-nlp-foundations-to-advanced/19-subword-tokenization/outputs) |
| 20 | Structured Outputs & Constrained Decoding | Build | ~60 minutes | [code](phases/05-nlp-foundations-to-advanced/20-structured-outputs-constrained-decoding/code) · [take-away files](phases/05-nlp-foundations-to-advanced/20-structured-outputs-constrained-decoding/outputs) |
| 21 | Natural Language Inference, Textual Entailment | Learn | ~60 minutes | [code](phases/05-nlp-foundations-to-advanced/21-nli-textual-entailment/code) · [take-away files](phases/05-nlp-foundations-to-advanced/21-nli-textual-entailment/outputs) |
| 22 | Embedding Models, The 2026 Deep Dive | Learn | ~60 minutes | [code](phases/05-nlp-foundations-to-advanced/22-embedding-models-deep-dive/code) · [take-away files](phases/05-nlp-foundations-to-advanced/22-embedding-models-deep-dive/outputs) |
| 23 | Chunking Strategies for RAG | Build | ~60 minutes | [code](phases/05-nlp-foundations-to-advanced/23-chunking-strategies-rag/code) · [take-away files](phases/05-nlp-foundations-to-advanced/23-chunking-strategies-rag/outputs) |
| 24 | Coreference Resolution | Learn | ~60 minutes | [code](phases/05-nlp-foundations-to-advanced/24-coreference-resolution/code) · [take-away files](phases/05-nlp-foundations-to-advanced/24-coreference-resolution/outputs) |
| 25 | Entity Linking & Disambiguation | Build | ~60 minutes | [code](phases/05-nlp-foundations-to-advanced/25-entity-linking/code) · [take-away files](phases/05-nlp-foundations-to-advanced/25-entity-linking/outputs) |
| 26 | Relation Extraction & Knowledge Graph Construction | Build | ~60 minutes | [code](phases/05-nlp-foundations-to-advanced/26-relation-extraction-kg/code) · [take-away files](phases/05-nlp-foundations-to-advanced/26-relation-extraction-kg/outputs) |
| 27 | LLM Evaluation, RAGAS, DeepEval, G-Eval | Build | ~75 minutes | [code](phases/05-nlp-foundations-to-advanced/27-llm-evaluation-frameworks/code) · [take-away files](phases/05-nlp-foundations-to-advanced/27-llm-evaluation-frameworks/outputs) |
| 28 | Long-Context Evaluation, NIAH, RULER, LongBench, MRCR | Learn | ~60 minutes | [code](phases/05-nlp-foundations-to-advanced/28-long-context-evaluation/code) · [take-away files](phases/05-nlp-foundations-to-advanced/28-long-context-evaluation/outputs) |
| 29 | Dialogue State Tracking | Build | ~75 minutes | [code](phases/05-nlp-foundations-to-advanced/29-dialogue-state-tracking/code) · [take-away files](phases/05-nlp-foundations-to-advanced/29-dialogue-state-tracking/outputs) |

### Phase 6: Speech & Audio

Hear, understand, speak.

| # | Lesson | Type | Time | Files |
|---|---|---|---|---|
| 01 | Audio Fundamentals, Waveforms, Sampling, Fourier Transform | Learn | ~45 minutes | [code](phases/06-speech-and-audio/01-audio-fundamentals/code) · [take-away files](phases/06-speech-and-audio/01-audio-fundamentals/outputs) |
| 02 | Spectrograms, Mel Scale & Audio Features | Build | ~45 minutes | [code](phases/06-speech-and-audio/02-spectrograms-mel-features/code) · [take-away files](phases/06-speech-and-audio/02-spectrograms-mel-features/outputs) |
| 03 | Audio Classification, From k-NN on MFCCs to AST and BEATs | Build | ~75 minutes | [code](phases/06-speech-and-audio/03-audio-classification/code) · [take-away files](phases/06-speech-and-audio/03-audio-classification/outputs) |
| 04 | Speech Recognition (ASR), CTC, RNN-T, Attention | Build | ~45 minutes | [code](phases/06-speech-and-audio/04-speech-recognition-asr/code) · [take-away files](phases/06-speech-and-audio/04-speech-recognition-asr/outputs) |
| 05 | Whisper, Architecture & Fine-Tuning | Build | ~75 minutes | [code](phases/06-speech-and-audio/05-whisper-architecture-finetuning/code) · [take-away files](phases/06-speech-and-audio/05-whisper-architecture-finetuning/outputs) |
| 06 | Speaker Recognition & Verification | Build | ~45 minutes | [code](phases/06-speech-and-audio/06-speaker-recognition-verification/code) · [take-away files](phases/06-speech-and-audio/06-speaker-recognition-verification/outputs) |
| 07 | Text-to-Speech (TTS), From Tacotron to F5 and Kokoro | Build | ~75 minutes | [code](phases/06-speech-and-audio/07-text-to-speech/code) · [take-away files](phases/06-speech-and-audio/07-text-to-speech/outputs) |
| 08 | Voice Cloning & Voice Conversion | Build | ~75 minutes | [code](phases/06-speech-and-audio/08-voice-cloning-conversion/code) · [take-away files](phases/06-speech-and-audio/08-voice-cloning-conversion/outputs) |
| 09 | Music Generation, MusicGen, Stable Audio, Suno, and the Licensing Earthquake | Build | ~75 minutes | [code](phases/06-speech-and-audio/09-music-generation/code) · [take-away files](phases/06-speech-and-audio/09-music-generation/outputs) |
| 10 | Audio-Language Models, Qwen2.5-Omni, Audio Flamingo, GPT-4o Audio | Learn | ~45 minutes | [code](phases/06-speech-and-audio/10-audio-language-models/code) · [take-away files](phases/06-speech-and-audio/10-audio-language-models/outputs) |
| 11 | Real-Time Audio Processing | Build | ~75 minutes | [code](phases/06-speech-and-audio/11-real-time-audio-processing/code) · [take-away files](phases/06-speech-and-audio/11-real-time-audio-processing/outputs) |
| 12 | Build a Voice Assistant Pipeline, The Phase 6 Capstone | Build | ~120 minutes | [code](phases/06-speech-and-audio/12-voice-assistant-pipeline/code) · [take-away files](phases/06-speech-and-audio/12-voice-assistant-pipeline/outputs) |
| 13 | Neural Audio Codecs, EnCodec, SNAC, Mimi, DAC and the Semantic-Acoustic Split | Learn | ~60 minutes | [code](phases/06-speech-and-audio/13-neural-audio-codecs/code) · [take-away files](phases/06-speech-and-audio/13-neural-audio-codecs/outputs) |
| 14 | Voice Activity Detection & Turn-Taking, Silero, Cobra, and the Flush Trick | Build | ~45 minutes | [code](phases/06-speech-and-audio/14-voice-activity-detection-turn-taking/code) · [take-away files](phases/06-speech-and-audio/14-voice-activity-detection-turn-taking/outputs) |
| 15 | Streaming Speech-to-Speech, Moshi, Hibiki, and Full-Duplex Dialogue | Learn | ~75 minutes | [code](phases/06-speech-and-audio/15-streaming-speech-to-speech-moshi-hibiki/code) · [take-away files](phases/06-speech-and-audio/15-streaming-speech-to-speech-moshi-hibiki/outputs) |
| 16 | Voice Anti-Spoofing & Audio Watermarking, ASVspoof 5, AudioSeal, WaveVerify | Build | ~75 minutes | [code](phases/06-speech-and-audio/16-anti-spoofing-audio-watermarking/code) · [take-away files](phases/06-speech-and-audio/16-anti-spoofing-audio-watermarking/outputs) |
| 17 | Audio Evaluation, WER, MOS, UTMOS, MMAU, FAD, and the Open Leaderboards | Learn | ~60 minutes | [code](phases/06-speech-and-audio/17-audio-evaluation-metrics/code) · [take-away files](phases/06-speech-and-audio/17-audio-evaluation-metrics/outputs) |

### Phase 7: Transformers Deep Dive

The architecture that changed everything.

| # | Lesson | Type | Time | Files |
|---|---|---|---|---|
| 01 | Why Transformers, The Problems with RNNs | Learn | ~45 minutes | [code](phases/07-transformers-deep-dive/01-why-transformers/code) · [take-away files](phases/07-transformers-deep-dive/01-why-transformers/outputs) |
| 02 | Self-Attention from Scratch | Build | ~90 minutes | [code](phases/07-transformers-deep-dive/02-self-attention-from-scratch/code) · [take-away files](phases/07-transformers-deep-dive/02-self-attention-from-scratch/outputs) |
| 03 | Multi-Head Attention | Build | ~75 minutes | [code](phases/07-transformers-deep-dive/03-multi-head-attention/code) · [take-away files](phases/07-transformers-deep-dive/03-multi-head-attention/outputs) |
| 04 | Positional Encoding, Sinusoidal, RoPE, ALiBi | Build | ~45 minutes | [code](phases/07-transformers-deep-dive/04-positional-encoding/code) · [take-away files](phases/07-transformers-deep-dive/04-positional-encoding/outputs) |
| 05 | The Full Transformer, Encoder + Decoder | Build | ~75 minutes | [code](phases/07-transformers-deep-dive/05-full-transformer/code) · [take-away files](phases/07-transformers-deep-dive/05-full-transformer/outputs) |
| 06 | BERT, Masked Language Modeling | Build | ~45 minutes | [code](phases/07-transformers-deep-dive/06-bert-masked-language-modeling/code) · [take-away files](phases/07-transformers-deep-dive/06-bert-masked-language-modeling/outputs) |
| 07 | GPT, Causal Language Modeling | Build | ~75 minutes | [code](phases/07-transformers-deep-dive/07-gpt-causal-language-modeling/code) · [take-away files](phases/07-transformers-deep-dive/07-gpt-causal-language-modeling/outputs) |
| 08 | T5, BART, Encoder-Decoder Models | Learn | ~45 minutes | [code](phases/07-transformers-deep-dive/08-t5-bart-encoder-decoder/code) · [take-away files](phases/07-transformers-deep-dive/08-t5-bart-encoder-decoder/outputs) |
| 09 | Vision Transformers (ViT) | Build | ~45 minutes | [code](phases/07-transformers-deep-dive/09-vision-transformers/code) · [take-away files](phases/07-transformers-deep-dive/09-vision-transformers/outputs) |
| 10 | Audio Transformers, Whisper Architecture | Learn | ~45 minutes | [code](phases/07-transformers-deep-dive/10-audio-transformers-whisper/code) · [take-away files](phases/07-transformers-deep-dive/10-audio-transformers-whisper/outputs) |
| 11 | Mixture of Experts (MoE) | Build | ~45 minutes | [code](phases/07-transformers-deep-dive/11-mixture-of-experts/code) · [take-away files](phases/07-transformers-deep-dive/11-mixture-of-experts/outputs) |
| 12 | KV Cache, Flash Attention & Inference Optimization | Build | ~75 minutes | [code](phases/07-transformers-deep-dive/12-kv-cache-flash-attention/code) · [take-away files](phases/07-transformers-deep-dive/12-kv-cache-flash-attention/outputs) |
| 13 | Scaling Laws | Learn | ~45 minutes | [code](phases/07-transformers-deep-dive/13-scaling-laws/code) · [take-away files](phases/07-transformers-deep-dive/13-scaling-laws/outputs) |
| 14 | Build a Transformer from Scratch, The Capstone | Build | ~120 minutes | [code](phases/07-transformers-deep-dive/14-build-a-transformer-capstone/code) · [take-away files](phases/07-transformers-deep-dive/14-build-a-transformer-capstone/outputs) |
| 15 | Attention Variants, Sliding Window, Sparse, Differential | Build | ~60 minutes | [code](phases/07-transformers-deep-dive/15-attention-variants/code) · [take-away files](phases/07-transformers-deep-dive/15-attention-variants/outputs) |
| 16 | Speculative Decoding, Draft, Verify, Repeat | Build | ~60 minutes | [code](phases/07-transformers-deep-dive/16-speculative-decoding/code) · [take-away files](phases/07-transformers-deep-dive/16-speculative-decoding/outputs) |

### Phase 8: Generative AI

Create images, video, audio, 3D, and more.

| # | Lesson | Type | Time | Files |
|---|---|---|---|---|
| 01 | Generative Models, Taxonomy & History | Learn | ~45 minutes | [code](phases/08-generative-ai/01-generative-models-taxonomy-history/code) · [take-away files](phases/08-generative-ai/01-generative-models-taxonomy-history/outputs) |
| 02 | Autoencoders & Variational Autoencoders (VAE) | Build | ~75 minutes | [code](phases/08-generative-ai/02-autoencoders-vae/code) · [take-away files](phases/08-generative-ai/02-autoencoders-vae/outputs) |
| 03 | GANs, Generator vs Discriminator | Build | ~75 minutes | [code](phases/08-generative-ai/03-gans-generator-discriminator/code) · [take-away files](phases/08-generative-ai/03-gans-generator-discriminator/outputs) |
| 04 | Conditional GANs & Pix2Pix | Build | ~75 minutes | [code](phases/08-generative-ai/04-conditional-gans-pix2pix/code) · [take-away files](phases/08-generative-ai/04-conditional-gans-pix2pix/outputs) |
| 05 | StyleGAN | Build | ~45 minutes | [code](phases/08-generative-ai/05-stylegan/code) · [take-away files](phases/08-generative-ai/05-stylegan/outputs) |
| 06 | Diffusion Models, DDPM from Scratch | Build | ~75 minutes | [code](phases/08-generative-ai/06-diffusion-ddpm-from-scratch/code) · [take-away files](phases/08-generative-ai/06-diffusion-ddpm-from-scratch/outputs) |
| 07 | Latent Diffusion & Stable Diffusion | Build | ~75 minutes | [code](phases/08-generative-ai/07-latent-diffusion-stable-diffusion/code) · [take-away files](phases/08-generative-ai/07-latent-diffusion-stable-diffusion/outputs) |
| 08 | ControlNet, LoRA & Conditioning | Build | ~75 minutes | [code](phases/08-generative-ai/08-controlnet-lora-conditioning/code) · [take-away files](phases/08-generative-ai/08-controlnet-lora-conditioning/outputs) |
| 09 | Inpainting, Outpainting & Image Editing | Build | ~75 minutes | [code](phases/08-generative-ai/09-inpainting-outpainting-editing/code) · [take-away files](phases/08-generative-ai/09-inpainting-outpainting-editing/outputs) |
| 10 | Video Generation | Build | ~45 minutes | [code](phases/08-generative-ai/10-video-generation/code) · [take-away files](phases/08-generative-ai/10-video-generation/outputs) |
| 11 | Audio Generation | Build | ~45 minutes | [code](phases/08-generative-ai/11-audio-generation/code) · [take-away files](phases/08-generative-ai/11-audio-generation/outputs) |
| 12 | 3D Generation | Learn | ~45 minutes | [code](phases/08-generative-ai/12-3d-generation/code) · [take-away files](phases/08-generative-ai/12-3d-generation/outputs) |
| 13 | Flow Matching & Rectified Flows | Build | ~45 minutes | [code](phases/08-generative-ai/13-flow-matching-rectified-flows/code) · [take-away files](phases/08-generative-ai/13-flow-matching-rectified-flows/outputs) |
| 14 | Evaluation, FID, CLIP Score, Human Preference | Build | ~45 minutes | [code](phases/08-generative-ai/14-evaluation-fid-clip-score/code) · [take-away files](phases/08-generative-ai/14-evaluation-fid-clip-score/outputs) |
| 15 | Visual Autoregressive Modeling (VAR): Next-Scale Prediction | Build | ~90 minutes | [code](phases/08-generative-ai/19-visual-autoregressive-var/code) · [take-away files](phases/08-generative-ai/19-visual-autoregressive-var/outputs) |

### Phase 9: Reinforcement Learning

The foundation of RLHF and game-playing AI.

| # | Lesson | Type | Time | Files |
|---|---|---|---|---|
| 01 | MDPs, States, Actions & Rewards | Learn | ~45 minutes | [code](phases/09-reinforcement-learning/01-mdps-states-actions-rewards/code) · [take-away files](phases/09-reinforcement-learning/01-mdps-states-actions-rewards/outputs) |
| 02 | Dynamic Programming, Policy Iteration & Value Iteration | Build | ~75 minutes | [code](phases/09-reinforcement-learning/02-dynamic-programming/code) · [take-away files](phases/09-reinforcement-learning/02-dynamic-programming/outputs) |
| 03 | Monte Carlo Methods, Learning from Complete Episodes | Build | ~75 minutes | [code](phases/09-reinforcement-learning/03-monte-carlo-methods/code) · [take-away files](phases/09-reinforcement-learning/03-monte-carlo-methods/outputs) |
| 04 | Temporal Difference, Q-Learning & SARSA | Build | ~75 minutes | [code](phases/09-reinforcement-learning/04-q-learning-sarsa/code) · [take-away files](phases/09-reinforcement-learning/04-q-learning-sarsa/outputs) |
| 05 | Deep Q-Networks (DQN) | Build | ~75 minutes | [code](phases/09-reinforcement-learning/05-dqn/code) · [take-away files](phases/09-reinforcement-learning/05-dqn/outputs) |
| 06 | Policy Gradient, REINFORCE from Scratch | Build | ~75 minutes | [code](phases/09-reinforcement-learning/06-policy-gradients-reinforce/code) · [take-away files](phases/09-reinforcement-learning/06-policy-gradients-reinforce/outputs) |
| 07 | Actor-Critic, A2C and A3C | Build | ~75 minutes | [code](phases/09-reinforcement-learning/07-actor-critic-a2c-a3c/code) · [take-away files](phases/09-reinforcement-learning/07-actor-critic-a2c-a3c/outputs) |
| 08 | Proximal Policy Optimization (PPO) | Build | ~75 minutes | [code](phases/09-reinforcement-learning/08-ppo/code) · [take-away files](phases/09-reinforcement-learning/08-ppo/outputs) |
| 09 | Reward Modeling & RLHF | Build | ~45 minutes | [code](phases/09-reinforcement-learning/09-reward-modeling-rlhf/code) · [take-away files](phases/09-reinforcement-learning/09-reward-modeling-rlhf/outputs) |
| 10 | Multi-Agent RL | Build | ~45 minutes | [code](phases/09-reinforcement-learning/10-multi-agent-rl/code) · [take-away files](phases/09-reinforcement-learning/10-multi-agent-rl/outputs) |
| 11 | Sim-to-Real Transfer | Learn | ~45 minutes | [code](phases/09-reinforcement-learning/11-sim-to-real-transfer/code) · [take-away files](phases/09-reinforcement-learning/11-sim-to-real-transfer/outputs) |
| 12 | RL for Games, AlphaZero, MuZero, and the LLM-Reasoning Era | Build | ~120 minutes | [code](phases/09-reinforcement-learning/12-rl-for-games/code) · [take-away files](phases/09-reinforcement-learning/12-rl-for-games/outputs) |

### Phase 10: LLMs from Scratch

Build, train, and understand large language models.

| # | Lesson | Type | Time | Files |
|---|---|---|---|---|
| 01 | Tokenizers: BPE, WordPiece, SentencePiece | Build | ~90 minutes | [code](phases/10-llms-from-scratch/01-tokenizers/code) · [take-away files](phases/10-llms-from-scratch/01-tokenizers/outputs) |
| 02 | Building a Tokenizer from Scratch | Build | ~90 minutes | [code](phases/10-llms-from-scratch/02-building-a-tokenizer/code) · [take-away files](phases/10-llms-from-scratch/02-building-a-tokenizer/outputs) |
| 03 | Data Pipelines for Pre-Training | Build | ~90 minutes | [code](phases/10-llms-from-scratch/03-data-pipelines/code) · [take-away files](phases/10-llms-from-scratch/03-data-pipelines/outputs) |
| 04 | Pre-Training a Mini GPT (124M Parameters) | Build | ~120 minutes | [code](phases/10-llms-from-scratch/04-pre-training-mini-gpt/code) · [take-away files](phases/10-llms-from-scratch/04-pre-training-mini-gpt/outputs) |
| 05 | Scaling: Distributed Training, FSDP, DeepSpeed | Build | ~120 minutes | [code](phases/10-llms-from-scratch/05-scaling-distributed/code) · [take-away files](phases/10-llms-from-scratch/05-scaling-distributed/outputs) |
| 06 | Instruction Tuning (SFT) | Build | ~90 minutes | [code](phases/10-llms-from-scratch/06-instruction-tuning-sft/code) · [take-away files](phases/10-llms-from-scratch/06-instruction-tuning-sft/outputs) |
| 07 | RLHF: Reward Model + PPO | Build | ~90 minutes | [code](phases/10-llms-from-scratch/07-rlhf/code) · [take-away files](phases/10-llms-from-scratch/07-rlhf/outputs) |
| 08 | DPO: Direct Preference Optimization | Build | ~90 minutes | [code](phases/10-llms-from-scratch/08-dpo/code) · [take-away files](phases/10-llms-from-scratch/08-dpo/outputs) |
| 09 | Constitutional AI and Self-Improvement | Build | ~45 minutes | [code](phases/10-llms-from-scratch/09-constitutional-ai-self-improvement/code) · [take-away files](phases/10-llms-from-scratch/09-constitutional-ai-self-improvement/outputs) |
| 10 | Evaluation: Benchmarks, Evals, LM Harness | Build | ~90 minutes | [code](phases/10-llms-from-scratch/10-evaluation/code) · [take-away files](phases/10-llms-from-scratch/10-evaluation/outputs) |
| 11 | Quantization: Making Models Fit | Build | ~120 minutes | [code](phases/10-llms-from-scratch/11-quantization/code) · [take-away files](phases/10-llms-from-scratch/11-quantization/outputs) |
| 12 | Inference Optimization | Build | ~120 minutes | [code](phases/10-llms-from-scratch/12-inference-optimization/code) · [take-away files](phases/10-llms-from-scratch/12-inference-optimization/outputs) |
| 13 | Building a Complete LLM Pipeline | Build | ~120 minutes | [code](phases/10-llms-from-scratch/13-building-complete-llm-pipeline/code) · [take-away files](phases/10-llms-from-scratch/13-building-complete-llm-pipeline/outputs) |
| 14 | Open Models: Architecture Walkthroughs | Learn | ~45 minutes | [code](phases/10-llms-from-scratch/14-open-models-architecture-walkthroughs/code) · [take-away files](phases/10-llms-from-scratch/14-open-models-architecture-walkthroughs/outputs) |
| 15 | Speculative Decoding and EAGLE-3 | Build | ~75 minutes | [code](phases/10-llms-from-scratch/15-speculative-decoding-eagle3/code) · [take-away files](phases/10-llms-from-scratch/15-speculative-decoding-eagle3/outputs) |
| 16 | Differential Attention (V2) | Build | ~60 minutes | [code](phases/10-llms-from-scratch/16-differential-attention-v2/code) · [take-away files](phases/10-llms-from-scratch/16-differential-attention-v2/outputs) |
| 17 | Native Sparse Attention (DeepSeek NSA) | Build | ~60 minutes | [code](phases/10-llms-from-scratch/17-native-sparse-attention/code) · [take-away files](phases/10-llms-from-scratch/17-native-sparse-attention/outputs) |
| 18 | Multi-Token Prediction (MTP) | Build | ~60 minutes | [code](phases/10-llms-from-scratch/18-multi-token-prediction/code) · [take-away files](phases/10-llms-from-scratch/18-multi-token-prediction/outputs) |
| 19 | DualPipe Parallelism | Learn | ~60 minutes | [code](phases/10-llms-from-scratch/19-dualpipe-parallelism/code) · [take-away files](phases/10-llms-from-scratch/19-dualpipe-parallelism/outputs) |
| 20 | DeepSeek-V3 Architecture Walkthrough | Learn | ~75 minutes | [code](phases/10-llms-from-scratch/20-deepseek-v3-walkthrough/code) · [take-away files](phases/10-llms-from-scratch/20-deepseek-v3-walkthrough/outputs) |
| 21 | Jamba, Hybrid SSM-Transformer | Learn | ~60 minutes | [code](phases/10-llms-from-scratch/21-jamba-hybrid-ssm-transformer/code) · [take-away files](phases/10-llms-from-scratch/21-jamba-hybrid-ssm-transformer/outputs) |
| 22 | Async and Hogwild! Inference | Build | ~60 minutes | [code](phases/10-llms-from-scratch/22-async-hogwild-inference/code) · [take-away files](phases/10-llms-from-scratch/22-async-hogwild-inference/outputs) |
| 23 | Speculative Decoding and EAGLE | Build | ~75 minutes | [code](phases/10-llms-from-scratch/25-speculative-decoding/code) · [take-away files](phases/10-llms-from-scratch/25-speculative-decoding/outputs) |
| 24 | Gradient Checkpointing and Activation Recomputation | Build | ~70 minutes | [code](phases/10-llms-from-scratch/34-gradient-checkpointing/code) · [take-away files](phases/10-llms-from-scratch/34-gradient-checkpointing/outputs) |

### Phase 11: LLM Engineering

Put LLMs to work in production.

| # | Lesson | Type | Time | Files |
|---|---|---|---|---|
| 01 | Prompt Engineering: Techniques & Patterns | Build | ~90 minutes | [code](phases/11-llm-engineering/01-prompt-engineering/code) · [take-away files](phases/11-llm-engineering/01-prompt-engineering/outputs) |
| 02 | Few-Shot, Chain-of-Thought, Tree-of-Thought | Build | ~45 minutes | [code](phases/11-llm-engineering/02-few-shot-cot/code) · [take-away files](phases/11-llm-engineering/02-few-shot-cot/outputs) |
| 03 | Structured Outputs: JSON, Schema Validation, Constrained Decoding | Build | ~90 minutes | [code](phases/11-llm-engineering/03-structured-outputs/code) · [take-away files](phases/11-llm-engineering/03-structured-outputs/outputs) |
| 04 | Embeddings & Vector Representations | Build | ~75 minutes | [code](phases/11-llm-engineering/04-embeddings/code) · [take-away files](phases/11-llm-engineering/04-embeddings/outputs) |
| 05 | Context Engineering: Windows, Budgets, Memory, and Retrieval | Build | ~90 minutes | [code](phases/11-llm-engineering/05-context-engineering/code) · [take-away files](phases/11-llm-engineering/05-context-engineering/outputs) |
| 06 | RAG (Retrieval-Augmented Generation) | Build | ~90 minutes | [code](phases/11-llm-engineering/06-rag/code) · [take-away files](phases/11-llm-engineering/06-rag/outputs) |
| 07 | Advanced RAG (Chunking, Reranking, Hybrid Search) | Build | ~90 minutes | [code](phases/11-llm-engineering/07-advanced-rag/code) · [take-away files](phases/11-llm-engineering/07-advanced-rag/outputs) |
| 08 | Fine-Tuning with LoRA & QLoRA | Build | ~75 minutes | [code](phases/11-llm-engineering/08-fine-tuning-lora/code) · [take-away files](phases/11-llm-engineering/08-fine-tuning-lora/outputs) |
| 09 | Function Calling & Tool Use | Build | ~75 minutes | [code](phases/11-llm-engineering/09-function-calling/code) · [take-away files](phases/11-llm-engineering/09-function-calling/outputs) |
| 10 | Evaluation & Testing LLM Applications | Build | ~45 minutes | [code](phases/11-llm-engineering/10-evaluation/code) · [take-away files](phases/11-llm-engineering/10-evaluation/outputs) |
| 11 | Caching, Rate Limiting & Cost Optimization | Build | ~45 minutes | [code](phases/11-llm-engineering/11-caching-cost/code) · [take-away files](phases/11-llm-engineering/11-caching-cost/outputs) |
| 12 | Guardrails, Safety & Content Filtering | Build | ~45 minutes | [code](phases/11-llm-engineering/12-guardrails/code) · [take-away files](phases/11-llm-engineering/12-guardrails/outputs) |
| 13 | Building a Production LLM Application | Build (Capstone) | ~120 minutes | [code](phases/11-llm-engineering/13-production-app/code) · [take-away files](phases/11-llm-engineering/13-production-app/outputs) |
| 14 | Model Context Protocol (MCP) | Build | ~75 minutes | [code](phases/11-llm-engineering/14-model-context-protocol/code) · [take-away files](phases/11-llm-engineering/14-model-context-protocol/outputs) |
| 15 | Prompt Caching and Context Caching | Build | ~60 minutes | [code](phases/11-llm-engineering/15-prompt-caching/code) · [take-away files](phases/11-llm-engineering/15-prompt-caching/outputs) |
| 16 | Agent State Machines, Graphs, Nodes, Checkpoints | Build | ~75 minutes | [code](phases/11-llm-engineering/16-langgraph-state-machines/code) · [take-away files](phases/11-llm-engineering/16-langgraph-state-machines/outputs) |
| 17 | Agent Framework Tradeoffs, Graph, Role, and Actor Orchestration | Learn | ~45 minutes | [code](phases/11-llm-engineering/17-agent-framework-tradeoffs/code) · [take-away files](phases/11-llm-engineering/17-agent-framework-tradeoffs/outputs) |

### Phase 12: Multimodal AI

See, hear, read, and reason across modalities, from ViT patches to computer-use agents.

| # | Lesson | Type | Time | Files |
|---|---|---|---|---|
| 01 | Vision Transformers and the Patch-Token Primitive | Learn | ~120 minutes | [code](phases/12-multimodal-ai/01-vision-transformer-patch-tokens/code) · [take-away files](phases/12-multimodal-ai/01-vision-transformer-patch-tokens/outputs) |
| 02 | CLIP and Contrastive Vision-Language Pretraining | Build | ~180 minutes | [code](phases/12-multimodal-ai/02-clip-contrastive-pretraining/code) · [take-away files](phases/12-multimodal-ai/02-clip-contrastive-pretraining/outputs) |
| 03 | From CLIP to BLIP-2, Q-Former as Modality Bridge | Build | ~180 minutes | [code](phases/12-multimodal-ai/03-blip2-qformer-bridge/code) · [take-away files](phases/12-multimodal-ai/03-blip2-qformer-bridge/outputs) |
| 04 | Flamingo and Gated Cross-Attention for Few-Shot VLMs | Learn | ~120 minutes | [code](phases/12-multimodal-ai/04-flamingo-gated-cross-attention/code) · [take-away files](phases/12-multimodal-ai/04-flamingo-gated-cross-attention/outputs) |
| 05 | LLaVA and Visual Instruction Tuning | Build | ~180 minutes | [code](phases/12-multimodal-ai/05-llava-visual-instruction-tuning/code) · [take-away files](phases/12-multimodal-ai/05-llava-visual-instruction-tuning/outputs) |
| 06 | Any-Resolution Vision: Patch-n'-Pack and NaFlex | Build | ~120 minutes | [code](phases/12-multimodal-ai/06-any-resolution-patch-n-pack/code) · [take-away files](phases/12-multimodal-ai/06-any-resolution-patch-n-pack/outputs) |
| 07 | Open-Weight VLM Recipes: What Actually Matters | Learn + lab | ~180 minutes | [code](phases/12-multimodal-ai/07-open-weight-vlm-recipes/code) · [take-away files](phases/12-multimodal-ai/07-open-weight-vlm-recipes/outputs) |
| 08 | LLaVA-OneVision: Single-Image, Multi-Image, Video in One Model | Build | ~180 minutes | [code](phases/12-multimodal-ai/08-llava-onevision-single-multi-video/code) · [take-away files](phases/12-multimodal-ai/08-llava-onevision-single-multi-video/outputs) |
| 09 | Qwen-VL Family and Dynamic-FPS Video | Learn | ~120 minutes | [code](phases/12-multimodal-ai/09-qwen-vl-family-dynamic-fps/code) · [take-away files](phases/12-multimodal-ai/09-qwen-vl-family-dynamic-fps/outputs) |
| 10 | InternVL3: Native Multimodal Pretraining | Learn | ~120 minutes | [code](phases/12-multimodal-ai/10-internvl3-native-multimodal/code) · [take-away files](phases/12-multimodal-ai/10-internvl3-native-multimodal/outputs) |
| 11 | Chameleon and Early-Fusion Token-Only Multimodal Models | Build | ~180 minutes | [code](phases/12-multimodal-ai/11-chameleon-early-fusion-tokens/code) · [take-away files](phases/12-multimodal-ai/11-chameleon-early-fusion-tokens/outputs) |
| 12 | Emu3: Next-Token Prediction for Image and Video Generation | Learn | ~120 minutes | [code](phases/12-multimodal-ai/12-emu3-next-token-for-generation/code) · [take-away files](phases/12-multimodal-ai/12-emu3-next-token-for-generation/outputs) |
| 13 | Transfusion: Autoregressive Text + Diffusion Image in One Transformer | Build | ~180 minutes | [code](phases/12-multimodal-ai/13-transfusion-autoregressive-diffusion/code) · [take-away files](phases/12-multimodal-ai/13-transfusion-autoregressive-diffusion/outputs) |
| 14 | Show-o and Discrete-Diffusion Unified Models | Learn | ~120 minutes | [code](phases/12-multimodal-ai/14-show-o-discrete-diffusion-unified/code) · [take-away files](phases/12-multimodal-ai/14-show-o-discrete-diffusion-unified/outputs) |
| 15 | Janus-Pro: Decoupled Encoders for Unified Multimodal Models | Build | ~120 minutes | [code](phases/12-multimodal-ai/15-janus-pro-decoupled-encoders/code) · [take-away files](phases/12-multimodal-ai/15-janus-pro-decoupled-encoders/outputs) |
| 16 | MIO and Any-to-Any Streaming Multimodal Models | Learn | ~120 minutes | [code](phases/12-multimodal-ai/16-mio-any-to-any-streaming/code) · [take-away files](phases/12-multimodal-ai/16-mio-any-to-any-streaming/outputs) |
| 17 | Video-Language Models: Temporal Tokens and Grounding | Build | ~180 minutes | [code](phases/12-multimodal-ai/17-video-language-temporal-grounding/code) · [take-away files](phases/12-multimodal-ai/17-video-language-temporal-grounding/outputs) |
| 18 | Long-Video Understanding at Million-Token Context | Build | ~180 minutes | [code](phases/12-multimodal-ai/18-long-video-million-token/code) · [take-away files](phases/12-multimodal-ai/18-long-video-million-token/outputs) |
| 19 | Audio-Language Models: the Whisper to Audio Flamingo 3 Arc | Build | ~180 minutes | [code](phases/12-multimodal-ai/19-audio-language-whisper-to-af3/code) · [take-away files](phases/12-multimodal-ai/19-audio-language-whisper-to-af3/outputs) |
| 20 | Omni Models: Qwen2.5-Omni and the Thinker-Talker Split | Build | ~180 minutes | [code](phases/12-multimodal-ai/20-omni-models-thinker-talker/code) · [take-away files](phases/12-multimodal-ai/20-omni-models-thinker-talker/outputs) |
| 21 | Embodied VLAs: RT-2, OpenVLA, π0, GR00T | Learn | ~180 minutes | [code](phases/12-multimodal-ai/21-embodied-vlas-openvla-pi0-groot/code) · [take-away files](phases/12-multimodal-ai/21-embodied-vlas-openvla-pi0-groot/outputs) |
| 22 | Document and Diagram Understanding | Build | ~180 minutes | [code](phases/12-multimodal-ai/22-document-diagram-understanding/code) · [take-away files](phases/12-multimodal-ai/22-document-diagram-understanding/outputs) |
| 23 | ColPali and Vision-Native Document RAG | Build | ~180 minutes | [code](phases/12-multimodal-ai/23-colpali-vision-native-rag/code) · [take-away files](phases/12-multimodal-ai/23-colpali-vision-native-rag/outputs) |
| 24 | Multimodal RAG and Cross-Modal Retrieval | Build | ~180 minutes | [code](phases/12-multimodal-ai/24-multimodal-rag-cross-modal/code) · [take-away files](phases/12-multimodal-ai/24-multimodal-rag-cross-modal/outputs) |
| 25 | Multimodal Agents and Computer-Use (Capstone) | Capstone | ~240 minutes | [code](phases/12-multimodal-ai/25-multimodal-agents-computer-use/code) · [take-away files](phases/12-multimodal-ai/25-multimodal-agents-computer-use/outputs) |

### Phase 13: Tools & Protocols

The interfaces between AI and the real world.

| # | Lesson | Type | Time | Files |
|---|---|---|---|---|
| 01 | The Tool Interface, Why Agents Need Structured I/O | Learn | ~45 minutes | [code](phases/13-tools-and-protocols/01-the-tool-interface/code) · [take-away files](phases/13-tools-and-protocols/01-the-tool-interface/outputs) |
| 02 | Function Calling Deep Dive, OpenAI, Anthropic, Gemini | Build | ~75 minutes | [code](phases/13-tools-and-protocols/02-function-calling-deep-dive/code) · [take-away files](phases/13-tools-and-protocols/02-function-calling-deep-dive/outputs) |
| 03 | Parallel Tool Calls and Streaming with Tools | Build | ~75 minutes | [code](phases/13-tools-and-protocols/03-parallel-and-streaming-tool-calls/code) · [take-away files](phases/13-tools-and-protocols/03-parallel-and-streaming-tool-calls/outputs) |
| 04 | Structured Output, JSON Schema, Pydantic, Zod, Constrained Decoding | Build | ~75 minutes | [code](phases/13-tools-and-protocols/04-structured-output/code) · [take-away files](phases/13-tools-and-protocols/04-structured-output/outputs) |
| 05 | Tool Schema Design, Naming, Descriptions, Parameter Constraints | Learn | ~45 minutes | [code](phases/13-tools-and-protocols/05-tool-schema-design/code) · [take-away files](phases/13-tools-and-protocols/05-tool-schema-design/outputs) |
| 06 | MCP Fundamentals: Stateless Requests and JSON-RPC | Learn | ~55 minutes | [code](phases/13-tools-and-protocols/06-mcp-fundamentals/code) · [take-away files](phases/13-tools-and-protocols/06-mcp-fundamentals/outputs) |
| 07 | Building an MCP Server: Stateless Python and TypeScript | Build | ~85 minutes | [code](phases/13-tools-and-protocols/07-building-an-mcp-server/code) · [take-away files](phases/13-tools-and-protocols/07-building-an-mcp-server/outputs) |
| 08 | Building an MCP Client: Discovery, Routing, and Dual-Era Fallback | Build | ~85 minutes | [code](phases/13-tools-and-protocols/08-building-an-mcp-client/code) · [take-away files](phases/13-tools-and-protocols/08-building-an-mcp-client/outputs) |
| 09 | MCP Transports: stdio and Stateless Streamable HTTP | Learn | ~65 minutes | [code](phases/13-tools-and-protocols/09-mcp-transports/code) · [take-away files](phases/13-tools-and-protocols/09-mcp-transports/outputs) |
| 10 | MCP Resources and Prompts: Addressable Context for Stateless Servers | Build | ~60 minutes | [code](phases/13-tools-and-protocols/10-mcp-resources-and-prompts/code) · [take-away files](phases/13-tools-and-protocols/10-mcp-resources-and-prompts/outputs) |
| 11 | MCP Model Input: Sampling Migration and Stateless MRTR | Build | ~75 minutes | [code](phases/13-tools-and-protocols/11-mcp-sampling/code) · [take-away files](phases/13-tools-and-protocols/11-mcp-sampling/outputs) |
| 12 | Explicit Scope and Stateless Elicitation | Build | ~60 minutes | [code](phases/13-tools-and-protocols/12-mcp-roots-and-elicitation/code) · [take-away files](phases/13-tools-and-protocols/12-mcp-roots-and-elicitation/outputs) |
| 13 | MCP Tasks Extension: Durable Work on a Stateless Core | Build | ~90 minutes | [code](phases/13-tools-and-protocols/13-mcp-async-tasks/code) · [take-away files](phases/13-tools-and-protocols/13-mcp-async-tasks/outputs) |
| 14 | MCP Apps on the Stateless Protocol | Build | ~75 minutes | [code](phases/13-tools-and-protocols/14-mcp-apps/code) · [take-away files](phases/13-tools-and-protocols/14-mcp-apps/outputs) |
| 15 | MCP Security: Poisoned Metadata, Routing, and MRTR State | Learn | ~60 minutes | [code](phases/13-tools-and-protocols/15-mcp-security-tool-poisoning/code) · [take-away files](phases/13-tools-and-protocols/15-mcp-security-tool-poisoning/outputs) |
| 16 | MCP Authorization: CIMD, Issuer Binding, PKCE, and Step-Up | Build | ~90 minutes | [code](phases/13-tools-and-protocols/16-mcp-security-oauth-2-1/code) · [take-away files](phases/13-tools-and-protocols/16-mcp-security-oauth-2-1/outputs) |
| 17 | Stateless MCP Gateways and Registry Admission | Learn | ~75 minutes | [code](phases/13-tools-and-protocols/17-mcp-gateways-and-registries/code) · [take-away files](phases/13-tools-and-protocols/17-mcp-gateways-and-registries/outputs) |
| 18 | MCP Auth in Production: Issuer-Bound Enrollment and Tokens | Build | ~90 minutes | [code](phases/13-tools-and-protocols/18-mcp-auth-production/code) · [take-away files](phases/13-tools-and-protocols/18-mcp-auth-production/outputs) |
| 19 | A2A, Agent-to-Agent Protocol | Build | ~75 minutes | [code](phases/13-tools-and-protocols/19-a2a-protocol/code) · [take-away files](phases/13-tools-and-protocols/19-a2a-protocol/outputs) |
| 20 | OpenTelemetry GenAI, Tracing Tool Calls End-to-End | Build | ~75 minutes | [code](phases/13-tools-and-protocols/20-opentelemetry-genai/code) · [take-away files](phases/13-tools-and-protocols/20-opentelemetry-genai/outputs) |
| 21 | LLM Routing Layer, LiteLLM, OpenRouter, Portkey | Learn | ~45 minutes | [code](phases/13-tools-and-protocols/21-llm-routing-layer/code) · [take-away files](phases/13-tools-and-protocols/21-llm-routing-layer/outputs) |
| 22 | Agent Skills: Portable Contract and Runtime Boundary | Build | ~90 minutes | [code](phases/13-tools-and-protocols/22-skills-and-agent-sdks/code) · [take-away files](phases/13-tools-and-protocols/22-skills-and-agent-sdks/outputs) |
| 23 | Capstone: Stateless Tool Ecosystem | Build | ~120 minutes | [code](phases/13-tools-and-protocols/23-capstone-tool-ecosystem/code) · [take-away files](phases/13-tools-and-protocols/23-capstone-tool-ecosystem/outputs) |
| 24 | Skill Discovery and Progressive Disclosure | Build | ~105 minutes | [code](phases/13-tools-and-protocols/24-skill-discovery-and-progressive-disclosure/code) · [take-away files](phases/13-tools-and-protocols/24-skill-discovery-and-progressive-disclosure/outputs) |
| 25 | Skill Invocation and Routing | Build | ~105 minutes | [code](phases/13-tools-and-protocols/25-skill-invocation-and-routing/code) · [take-away files](phases/13-tools-and-protocols/25-skill-invocation-and-routing/outputs) |
| 26 | Skill Permissions, Sandboxes, and Trust | Build | ~120 minutes | [code](phases/13-tools-and-protocols/26-skill-permissions-sandboxes-and-trust/code) · [take-away files](phases/13-tools-and-protocols/26-skill-permissions-sandboxes-and-trust/outputs) |
| 27 | Skill Evals, Packaging, and Portability | Build | ~150 minutes | [code](phases/13-tools-and-protocols/27-skill-evals-packaging-and-portability/code) · [take-away files](phases/13-tools-and-protocols/27-skill-evals-packaging-and-portability/outputs) |
| 28 | MCP Tool Contracts and Content | Build | ~120 minutes | [code](phases/13-tools-and-protocols/28-mcp-tool-contracts-and-content/code) · [take-away files](phases/13-tools-and-protocols/28-mcp-tool-contracts-and-content/outputs) |
| 29 | MCP Reliability, Cancellation, and Flow Control | Build | ~120 minutes | [code](phases/13-tools-and-protocols/29-mcp-reliability-cancellation-and-flow-control/code) · [take-away files](phases/13-tools-and-protocols/29-mcp-reliability-cancellation-and-flow-control/outputs) |
| 30 | MCP Registry Supply Chain: Admission, Drift, and Rollback | Build | ~90 minutes | [code](phases/13-tools-and-protocols/30-mcp-registry-supply-chain-and-drift/code) · [take-away files](phases/13-tools-and-protocols/30-mcp-registry-supply-chain-and-drift/outputs) |
| 31 | MCP Conformance Engineering: Versioning, Evidence, and Operations | Build | ~100 minutes | [code](phases/13-tools-and-protocols/31-mcp-conformance-versioning-and-operations/code) · [take-away files](phases/13-tools-and-protocols/31-mcp-conformance-versioning-and-operations/outputs) |

### Phase 14: Agent Engineering

Build agents from first principles, use coding agents reliably, and shape the work before implementation.

| # | Lesson | Type | Time | Files |
|---|---|---|---|---|
| 01 | The Agent Loop: Observe, Think, Act | Build | ~60 minutes | [code](phases/14-agent-engineering/01-the-agent-loop/code) · [take-away files](phases/14-agent-engineering/01-the-agent-loop/outputs) |
| 02 | ReWOO and Plan-and-Execute: Decoupled Planning | Build | ~60 minutes | [code](phases/14-agent-engineering/02-rewoo-plan-and-execute/code) · [take-away files](phases/14-agent-engineering/02-rewoo-plan-and-execute/outputs) |
| 03 | Reflexion: Verbal Reinforcement Learning | Build | ~60 minutes | [code](phases/14-agent-engineering/03-reflexion-verbal-rl/code) · [take-away files](phases/14-agent-engineering/03-reflexion-verbal-rl/outputs) |
| 04 | Tree of Thoughts and LATS: Deliberate Search | Build | ~75 minutes | [code](phases/14-agent-engineering/04-tree-of-thoughts-lats/code) · [take-away files](phases/14-agent-engineering/04-tree-of-thoughts-lats/outputs) |
| 05 | Self-Refine and CRITIC: Iterative Output Improvement | Build | ~60 minutes | [code](phases/14-agent-engineering/05-self-refine-and-critic/code) · [take-away files](phases/14-agent-engineering/05-self-refine-and-critic/outputs) |
| 06 | Tool Use and Function Calling | Build | ~60 minutes | [code](phases/14-agent-engineering/06-tool-use-and-function-calling/code) · [take-away files](phases/14-agent-engineering/06-tool-use-and-function-calling/outputs) |
| 07 | Agent Memory, Virtual Context and Memory Paging | Build | ~75 minutes | [code](phases/14-agent-engineering/07-memory-virtual-context-memgpt/code) · [take-away files](phases/14-agent-engineering/07-memory-virtual-context-memgpt/outputs) |
| 08 | Memory Blocks and Sleep-Time Compute | Build | ~75 minutes | [code](phases/14-agent-engineering/08-memory-blocks-sleep-time-compute/code) · [take-away files](phases/14-agent-engineering/08-memory-blocks-sleep-time-compute/outputs) |
| 09 | Hybrid Memory: Vector + Graph + KV | Build | ~75 minutes | [code](phases/14-agent-engineering/09-hybrid-memory-mem0/code) · [take-away files](phases/14-agent-engineering/09-hybrid-memory-mem0/outputs) |
| 10 | Skill Libraries and Lifelong Learning (Voyager) | Build | ~75 minutes | [code](phases/14-agent-engineering/10-skill-libraries-voyager/code) · [take-away files](phases/14-agent-engineering/10-skill-libraries-voyager/outputs) |
| 11 | Planning with HTN and Evolutionary Search | Build | ~75 minutes | [code](phases/14-agent-engineering/11-planning-htn-and-evolutionary/code) · [take-away files](phases/14-agent-engineering/11-planning-htn-and-evolutionary/outputs) |
| 12 | Anthropic's Workflow Patterns: Simple Over Complex | Learn + Build | ~60 minutes | [code](phases/14-agent-engineering/12-anthropic-workflow-patterns/code) · [take-away files](phases/14-agent-engineering/12-anthropic-workflow-patterns/outputs) |
| 13 | Stateful Graph Orchestration, Durable Execution and Checkpoints | Learn + Build | ~75 minutes | [code](phases/14-agent-engineering/13-langgraph-stateful-graphs/code) · [take-away files](phases/14-agent-engineering/13-langgraph-stateful-graphs/outputs) |
| 14 | The Actor Model for Agents, Async Messages and Typed Runtimes | Learn + Build | ~75 minutes | [code](phases/14-agent-engineering/14-autogen-actor-model/code) · [take-away files](phases/14-agent-engineering/14-autogen-actor-model/outputs) |
| 15 | Role-Based Agent Teams, Roles, Tasks, Processes | Learn + Build | ~75 minutes | [code](phases/14-agent-engineering/15-crewai-role-based-crews/code) · [take-away files](phases/14-agent-engineering/15-crewai-role-based-crews/outputs) |
| 16 | OpenAI Agents SDK: Handoffs, Guardrails, Tracing | Learn + Build | ~75 minutes | [code](phases/14-agent-engineering/16-openai-agents-sdk/code) · [take-away files](phases/14-agent-engineering/16-openai-agents-sdk/outputs) |
| 17 | The Harness as a Library, Subagents and Session Store | Learn + Build | ~75 minutes | [code](phases/14-agent-engineering/17-claude-agent-sdk/code) · [take-away files](phases/14-agent-engineering/17-claude-agent-sdk/outputs) |
| 18 | Production Agent Runtimes, Fast Instantiation and Typed Workflows | Learn | ~45 minutes | [code](phases/14-agent-engineering/18-agno-and-mastra-runtimes/code) · [take-away files](phases/14-agent-engineering/18-agno-and-mastra-runtimes/outputs) |
| 19 | Benchmarks: SWE-bench, GAIA, AgentBench | Learn | ~60 minutes | [code](phases/14-agent-engineering/19-benchmarks-swebench-gaia/code) · [take-away files](phases/14-agent-engineering/19-benchmarks-swebench-gaia/outputs) |
| 20 | Benchmarks: WebArena and OSWorld | Learn | ~60 minutes | [code](phases/14-agent-engineering/20-benchmarks-webarena-osworld/code) · [take-away files](phases/14-agent-engineering/20-benchmarks-webarena-osworld/outputs) |
| 21 | Computer Use: Claude, OpenAI CUA, Gemini | Learn | ~60 minutes | [code](phases/14-agent-engineering/21-computer-use-agents/code) · [take-away files](phases/14-agent-engineering/21-computer-use-agents/outputs) |
| 22 | Voice Agents: Pipecat and LiveKit | Learn | ~60 minutes | [code](phases/14-agent-engineering/22-voice-agents-pipecat-livekit/code) · [take-away files](phases/14-agent-engineering/22-voice-agents-pipecat-livekit/outputs) |
| 23 | OpenTelemetry GenAI Semantic Conventions | Learn + Build | ~60 minutes | [code](phases/14-agent-engineering/23-otel-genai-conventions/code) · [take-away files](phases/14-agent-engineering/23-otel-genai-conventions/outputs) |
| 24 | Agent Observability: Langfuse, Phoenix, Opik | Learn | ~45 minutes | [code](phases/14-agent-engineering/24-agent-observability-platforms/code) · [take-away files](phases/14-agent-engineering/24-agent-observability-platforms/outputs) |
| 25 | Multi-Agent Debate and Collaboration | Learn + Build | ~60 minutes | [code](phases/14-agent-engineering/25-multi-agent-debate/code) · [take-away files](phases/14-agent-engineering/25-multi-agent-debate/outputs) |
| 26 | Failure Modes: Why Agents Break | Learn + Build | ~60 minutes | [code](phases/14-agent-engineering/26-failure-modes-agentic/code) · [take-away files](phases/14-agent-engineering/26-failure-modes-agentic/outputs) |
| 27 | Prompt Injection and the PVE Defense | Build | ~75 minutes | [code](phases/14-agent-engineering/27-prompt-injection-defense/code) · [take-away files](phases/14-agent-engineering/27-prompt-injection-defense/outputs) |
| 28 | Orchestration Patterns: Supervisor, Swarm, Hierarchical | Learn + Build | ~60 minutes | [code](phases/14-agent-engineering/28-orchestration-patterns/code) · [take-away files](phases/14-agent-engineering/28-orchestration-patterns/outputs) |
| 29 | Production Runtimes: Queue, Event, Cron | Learn | ~60 minutes | [code](phases/14-agent-engineering/29-production-runtimes/code) · [take-away files](phases/14-agent-engineering/29-production-runtimes/outputs) |
| 30 | Eval-Driven Agent Development | Learn + Build | ~60 minutes | [code](phases/14-agent-engineering/30-eval-driven-agent-development/code) · [take-away files](phases/14-agent-engineering/30-eval-driven-agent-development/outputs) |
| 31 | Agent Workbench Engineering: Why Capable Models Still Fail | Learn + Build | ~45 minutes | [code](phases/14-agent-engineering/31-agent-workbench-why-models-fail/code) · [take-away files](phases/14-agent-engineering/31-agent-workbench-why-models-fail/outputs) |
| 32 | The Minimal Agent Workbench | Build | ~45 minutes | [code](phases/14-agent-engineering/32-minimal-agent-workbench/code) · [take-away files](phases/14-agent-engineering/32-minimal-agent-workbench/outputs) |
| 33 | Agent Instructions as Executable Constraints | Build | ~50 minutes | [code](phases/14-agent-engineering/33-instructions-as-executable-constraints/code) · [take-away files](phases/14-agent-engineering/33-instructions-as-executable-constraints/outputs) |
| 34 | Repo Memory and Durable State | Build | ~60 minutes | [code](phases/14-agent-engineering/34-repo-memory-and-state/code) · [take-away files](phases/14-agent-engineering/34-repo-memory-and-state/outputs) |
| 35 | Initialization Scripts for Agents | Build | ~45 minutes | [code](phases/14-agent-engineering/35-initialization-scripts/code) · [take-away files](phases/14-agent-engineering/35-initialization-scripts/outputs) |
| 36 | Scope Contracts and Task Boundaries | Build | ~50 minutes | [code](phases/14-agent-engineering/36-scope-contracts/code) · [take-away files](phases/14-agent-engineering/36-scope-contracts/outputs) |
| 37 | Runtime Feedback Loops | Build | ~50 minutes | [code](phases/14-agent-engineering/37-runtime-feedback-loops/code) · [take-away files](phases/14-agent-engineering/37-runtime-feedback-loops/outputs) |
| 38 | Verification Gates | Build | ~55 minutes | [code](phases/14-agent-engineering/38-verification-gates/code) · [take-away files](phases/14-agent-engineering/38-verification-gates/outputs) |
| 39 | Reviewer Agent: Separate Builder from Marker | Build | ~55 minutes | [code](phases/14-agent-engineering/39-reviewer-agent/code) · [take-away files](phases/14-agent-engineering/39-reviewer-agent/outputs) |
| 40 | Multi-Session Handoff | Build | ~50 minutes | [code](phases/14-agent-engineering/40-multi-session-handoff/code) · [take-away files](phases/14-agent-engineering/40-multi-session-handoff/outputs) |
| 41 | The Workbench on a Real Repo | Build | ~60 minutes | [code](phases/14-agent-engineering/41-workbench-for-real-repos/code) · [take-away files](phases/14-agent-engineering/41-workbench-for-real-repos/outputs) |
| 42 | Capstone: Ship a Reusable Agent Workbench Pack | Build | ~75 minutes | [code](phases/14-agent-engineering/42-agent-workbench-capstone/code) · [take-away files](phases/14-agent-engineering/42-agent-workbench-capstone/outputs) |
| 43 | Frame the Task Before the Agent Writes Code | Learn + Build | ~60 minutes | [code](phases/14-agent-engineering/43-frame-the-task-before-code/code) · [take-away files](phases/14-agent-engineering/43-frame-the-task-before-code/outputs) |
| 44 | Build an Evidence-Backed Execution Plan | Learn + Build | ~65 minutes | [code](phases/14-agent-engineering/44-plan-from-evidence/code) · [take-away files](phases/14-agent-engineering/44-plan-from-evidence/outputs) |
| 45 | Delegate Agent Work with Isolation and Merge Contracts | Learn + Build | ~70 minutes | [code](phases/14-agent-engineering/45-delegate-with-isolation/code) · [take-away files](phases/14-agent-engineering/45-delegate-with-isolation/outputs) |
| 46 | Turn Every Agent Correction into a System Improvement | Learn + Build | ~65 minutes | [code](phases/14-agent-engineering/46-turn-feedback-into-system/code) · [take-away files](phases/14-agent-engineering/46-turn-feedback-into-system/outputs) |
| 47 | Define the Outcome Before You Choose the Output | Learn + Build | ~60 minutes | [code](phases/14-agent-engineering/47-outcomes-before-output/code) · [take-away files](phases/14-agent-engineering/47-outcomes-before-output/outputs) |
| 48 | Discover the Workflow People Actually Perform | Learn + Build | ~70 minutes | [code](phases/14-agent-engineering/48-discover-the-real-workflow/code) · [take-away files](phases/14-agent-engineering/48-discover-the-real-workflow/outputs) |
| 49 | Map Assumptions and Resolve the Riskiest One First | Learn + Build | ~65 minutes | [code](phases/14-agent-engineering/49-map-assumptions-and-risk/code) · [take-away files](phases/14-agent-engineering/49-map-assumptions-and-risk/outputs) |
| 50 | Choose the Smallest Slice That Can Change the Decision | Learn + Build | ~65 minutes | [code](phases/14-agent-engineering/50-choose-the-smallest-testable-slice/code) · [take-away files](phases/14-agent-engineering/50-choose-the-smallest-testable-slice/outputs) |
| 51 | Write Specifications That Preserve Judgment | Learn + Build | ~75 minutes | [code](phases/14-agent-engineering/51-write-specifications-that-preserve-judgment/code) · [take-away files](phases/14-agent-engineering/51-write-specifications-that-preserve-judgment/outputs) |
| 52 | Design Success Metrics Before the Result Exists | Learn + Build | ~70 minutes | [code](phases/14-agent-engineering/52-design-success-metrics/code) · [take-away files](phases/14-agent-engineering/52-design-success-metrics/outputs) |
| 53 | Choose Prototype, Pilot, or Production Deliberately | Learn + Build | ~70 minutes | [code](phases/14-agent-engineering/53-prototype-pilot-or-production/code) · [take-away files](phases/14-agent-engineering/53-prototype-pilot-or-production/outputs) |
| 54 | Build a Feedback Ratchet with Ownership and Retirement | Learn + Build | ~75 minutes | [code](phases/14-agent-engineering/54-build-the-feedback-ratchet/code) · [take-away files](phases/14-agent-engineering/54-build-the-feedback-ratchet/outputs) |

### Phase 15: Autonomous Systems

Long-horizon agents, self-improvement, and the 2026 safety stack.

| # | Lesson | Type | Time | Files |
|---|---|---|---|---|
| 01 | The Shift from Chatbots to Long-Horizon Agents | Learn | ~45 minutes | [code](phases/15-autonomous-systems/01-long-horizon-agents/code) · [take-away files](phases/15-autonomous-systems/01-long-horizon-agents/outputs) |
| 02 | STaR, V-STaR, Quiet-STaR, Self-Taught Reasoning | Learn | ~60 minutes | [code](phases/15-autonomous-systems/02-star-family-reasoning/code) · [take-away files](phases/15-autonomous-systems/02-star-family-reasoning/outputs) |
| 03 | AlphaEvolve, Evolutionary Coding Agents | Learn | ~60 minutes | [code](phases/15-autonomous-systems/03-alphaevolve-evolutionary-coding/code) · [take-away files](phases/15-autonomous-systems/03-alphaevolve-evolutionary-coding/outputs) |
| 04 | Darwin Godel Machine, Open-Ended Self-Modifying Agents | Learn | ~60 minutes | [code](phases/15-autonomous-systems/04-darwin-godel-machine/code) · [take-away files](phases/15-autonomous-systems/04-darwin-godel-machine/outputs) |
| 05 | AI Scientist v2, Workshop-Level Autonomous Research | Learn | ~60 minutes | [code](phases/15-autonomous-systems/05-ai-scientist-v2/code) · [take-away files](phases/15-autonomous-systems/05-ai-scientist-v2/outputs) |
| 06 | Automated Alignment Research (Anthropic AAR) | Learn | ~60 minutes | [code](phases/15-autonomous-systems/06-automated-alignment-research/code) · [take-away files](phases/15-autonomous-systems/06-automated-alignment-research/outputs) |
| 07 | Recursive Self-Improvement, Capability vs Alignment | Learn | ~60 minutes | [code](phases/15-autonomous-systems/07-recursive-self-improvement/code) · [take-away files](phases/15-autonomous-systems/07-recursive-self-improvement/outputs) |
| 08 | Bounded Self-Improvement Designs | Learn | ~60 minutes | [code](phases/15-autonomous-systems/08-bounded-self-improvement/code) · [take-away files](phases/15-autonomous-systems/08-bounded-self-improvement/outputs) |
| 09 | The Autonomous Coding Agent Landscape (2026) | Learn | ~45 minutes | [code](phases/15-autonomous-systems/09-coding-agent-landscape/code) · [take-away files](phases/15-autonomous-systems/09-coding-agent-landscape/outputs) |
| 10 | Permission Modes for Autonomous Agents | Learn | ~45 minutes | [code](phases/15-autonomous-systems/10-claude-code-permission-modes/code) · [take-away files](phases/15-autonomous-systems/10-claude-code-permission-modes/outputs) |
| 11 | Browser Agents and Long-Horizon Web Tasks | Learn | ~45 minutes | [code](phases/15-autonomous-systems/11-browser-agents/code) · [take-away files](phases/15-autonomous-systems/11-browser-agents/outputs) |
| 12 | Long-Running Background Agents: Durable Execution | Learn | ~60 minutes | [code](phases/15-autonomous-systems/12-durable-execution/code) · [take-away files](phases/15-autonomous-systems/12-durable-execution/outputs) |
| 13 | Action Budgets, Iteration Caps, and Cost Governors | Learn | ~60 minutes | [code](phases/15-autonomous-systems/13-cost-governors/code) · [take-away files](phases/15-autonomous-systems/13-cost-governors/outputs) |
| 14 | Kill Switches, Circuit Breakers, and Canary Tokens | Learn | ~60 minutes | [code](phases/15-autonomous-systems/14-kill-switches-canaries/code) · [take-away files](phases/15-autonomous-systems/14-kill-switches-canaries/outputs) |
| 15 | Human-in-the-Loop: Propose-Then-Commit | Learn | ~60 minutes | [code](phases/15-autonomous-systems/15-propose-then-commit/code) · [take-away files](phases/15-autonomous-systems/15-propose-then-commit/outputs) |
| 16 | Checkpoints and Rollback | Learn | ~60 minutes | [code](phases/15-autonomous-systems/16-checkpoints-rollback/code) · [take-away files](phases/15-autonomous-systems/16-checkpoints-rollback/outputs) |
| 17 | Constitutional AI and Rule Overrides | Learn | ~60 minutes | [code](phases/15-autonomous-systems/17-constitutional-ai/code) · [take-away files](phases/15-autonomous-systems/17-constitutional-ai/outputs) |
| 18 | Llama Guard and Input/Output Classification | Learn | ~45 minutes | [code](phases/15-autonomous-systems/18-llama-guard/code) · [take-away files](phases/15-autonomous-systems/18-llama-guard/outputs) |
| 19 | Anthropic Responsible Scaling Policy v3.0 | Learn | ~45 minutes | [code](phases/15-autonomous-systems/19-anthropic-rsp/code) · [take-away files](phases/15-autonomous-systems/19-anthropic-rsp/outputs) |
| 20 | OpenAI Preparedness Framework and DeepMind Frontier Safety Framework | Learn | ~45 minutes | [code](phases/15-autonomous-systems/20-openai-preparedness-deepmind-fsf/code) · [take-away files](phases/15-autonomous-systems/20-openai-preparedness-deepmind-fsf/outputs) |
| 21 | METR Time Horizons and External Capability Evaluation | Learn | ~60 minutes | [code](phases/15-autonomous-systems/21-metr-external-evaluation/code) · [take-away files](phases/15-autonomous-systems/21-metr-external-evaluation/outputs) |
| 22 | CAIS, CAISI, and Societal-Scale Risk | Learn | ~45 minutes | [code](phases/15-autonomous-systems/22-cais-caisi-societal-risk/code) · [take-away files](phases/15-autonomous-systems/22-cais-caisi-societal-risk/outputs) |

### Phase 16: Multi-Agent & Swarms

Coordination, emergence, and collective intelligence.

| # | Lesson | Type | Time | Files |
|---|---|---|---|---|
| 01 | Why Multi-Agent? | Learn | ~60 minutes | [code](phases/16-multi-agent-and-swarms/01-why-multi-agent/code) · [take-away files](phases/16-multi-agent-and-swarms/01-why-multi-agent/outputs) |
| 02 | Heritage of FIPA-ACL and Speech Acts | Learn | ~60 minutes | [code](phases/16-multi-agent-and-swarms/02-fipa-acl-heritage/code) · [take-away files](phases/16-multi-agent-and-swarms/02-fipa-acl-heritage/outputs) |
| 03 | Communication Protocols | Build | ~120 minutes | [code](phases/16-multi-agent-and-swarms/03-communication-protocols/code) · [take-away files](phases/16-multi-agent-and-swarms/03-communication-protocols/outputs) |
| 04 | The Multi-Agent Primitive Model | Learn | ~60 minutes | [code](phases/16-multi-agent-and-swarms/04-primitive-model/code) · [take-away files](phases/16-multi-agent-and-swarms/04-primitive-model/outputs) |
| 05 | Supervisor / Orchestrator-Worker Pattern | Learn + Build | ~75 minutes | [code](phases/16-multi-agent-and-swarms/05-supervisor-orchestrator-pattern/code) · [take-away files](phases/16-multi-agent-and-swarms/05-supervisor-orchestrator-pattern/outputs) |
| 06 | Hierarchical Architecture and Its Failure Mode | Learn + Build | ~60 minutes | [code](phases/16-multi-agent-and-swarms/06-hierarchical-architecture/code) · [take-away files](phases/16-multi-agent-and-swarms/06-hierarchical-architecture/outputs) |
| 07 | Society of Mind and Multi-Agent Debate | Learn + Build | ~60 minutes | [code](phases/16-multi-agent-and-swarms/07-society-of-mind-debate/code) · [take-away files](phases/16-multi-agent-and-swarms/07-society-of-mind-debate/outputs) |
| 08 | Role Specialization, Planner, Critic, Executor, Verifier | Learn + Build | ~60 minutes | [code](phases/16-multi-agent-and-swarms/08-role-specialization/code) · [take-away files](phases/16-multi-agent-and-swarms/08-role-specialization/outputs) |
| 09 | Parallel / Swarm / Networked Architectures | Learn + Build | ~75 minutes | [code](phases/16-multi-agent-and-swarms/09-parallel-swarm-networks/code) · [take-away files](phases/16-multi-agent-and-swarms/09-parallel-swarm-networks/outputs) |
| 10 | Group Chat and Speaker Selection | Learn + Build | ~60 minutes | [code](phases/16-multi-agent-and-swarms/10-group-chat-speaker-selection/code) · [take-away files](phases/16-multi-agent-and-swarms/10-group-chat-speaker-selection/outputs) |
| 11 | Handoffs and Routines, Stateless Orchestration | Learn + Build | ~60 minutes | [code](phases/16-multi-agent-and-swarms/11-handoffs-and-routines/code) · [take-away files](phases/16-multi-agent-and-swarms/11-handoffs-and-routines/outputs) |
| 12 | A2A, The Agent-to-Agent Protocol | Learn + Build | ~75 minutes | [code](phases/16-multi-agent-and-swarms/12-a2a-protocol/code) · [take-away files](phases/16-multi-agent-and-swarms/12-a2a-protocol/outputs) |
| 13 | Shared Memory and Blackboard Patterns | Learn + Build | ~75 minutes | [code](phases/16-multi-agent-and-swarms/13-shared-memory-blackboard/code) · [take-away files](phases/16-multi-agent-and-swarms/13-shared-memory-blackboard/outputs) |
| 14 | Consensus and Byzantine Fault Tolerance for Agents | Learn + Build | ~75 minutes | [code](phases/16-multi-agent-and-swarms/14-consensus-and-bft/code) · [take-away files](phases/16-multi-agent-and-swarms/14-consensus-and-bft/outputs) |
| 15 | Voting, Self-Consistency, and Debate Topology | Learn + Build | ~75 minutes | [code](phases/16-multi-agent-and-swarms/15-voting-debate-topology/code) · [take-away files](phases/16-multi-agent-and-swarms/15-voting-debate-topology/outputs) |
| 16 | Negotiation and Bargaining | Learn + Build | ~75 minutes | [code](phases/16-multi-agent-and-swarms/16-negotiation-bargaining/code) · [take-away files](phases/16-multi-agent-and-swarms/16-negotiation-bargaining/outputs) |
| 17 | Generative Agents and Emergent Simulation | Learn + Build | ~75 minutes | [code](phases/16-multi-agent-and-swarms/17-generative-agents-simulation/code) · [take-away files](phases/16-multi-agent-and-swarms/17-generative-agents-simulation/outputs) |
| 18 | Theory of Mind and Emergent Coordination | Learn + Build | ~75 minutes | [code](phases/16-multi-agent-and-swarms/18-theory-of-mind-coordination/code) · [take-away files](phases/16-multi-agent-and-swarms/18-theory-of-mind-coordination/outputs) |
| 19 | Swarm Optimization for LLMs (PSO, ACO) | Learn + Build | ~75 minutes | [code](phases/16-multi-agent-and-swarms/19-swarm-optimization-pso-aco/code) · [take-away files](phases/16-multi-agent-and-swarms/19-swarm-optimization-pso-aco/outputs) |
| 20 | MARL, MADDPG, QMIX, MAPPO | Learn | ~90 minutes | [code](phases/16-multi-agent-and-swarms/20-marl-maddpg-qmix-mappo/code) · [take-away files](phases/16-multi-agent-and-swarms/20-marl-maddpg-qmix-mappo/outputs) |
| 21 | Agent Economies, Token Incentives, Reputation | Learn | ~75 minutes | [code](phases/16-multi-agent-and-swarms/21-agent-economies/code) · [take-away files](phases/16-multi-agent-and-swarms/21-agent-economies/outputs) |
| 22 | Production Scaling, Queues, Checkpoints, Durability | Learn + Build | ~75 minutes | [code](phases/16-multi-agent-and-swarms/22-production-scaling-queues-checkpoints/code) · [take-away files](phases/16-multi-agent-and-swarms/22-production-scaling-queues-checkpoints/outputs) |
| 23 | Failure Modes, MAST, Groupthink, Monoculture, Cascading Errors | Learn | ~75 minutes | [code](phases/16-multi-agent-and-swarms/23-failure-modes-mast-groupthink/code) · [take-away files](phases/16-multi-agent-and-swarms/23-failure-modes-mast-groupthink/outputs) |
| 24 | Evaluation and Coordination Benchmarks | Learn | ~75 minutes | [code](phases/16-multi-agent-and-swarms/24-evaluation-coordination-benchmarks/code) · [take-away files](phases/16-multi-agent-and-swarms/24-evaluation-coordination-benchmarks/outputs) |
| 25 | Case Studies and the 2026 State of the Art | Learn (capstone) | ~90 minutes | [code](phases/16-multi-agent-and-swarms/25-case-studies-2026-sota/code) · [take-away files](phases/16-multi-agent-and-swarms/25-case-studies-2026-sota/outputs) |

### Phase 17: Infrastructure & Production

Ship AI to the real world.

| # | Lesson | Type | Time | Files |
|---|---|---|---|---|
| 01 | Managed LLM Platforms, Bedrock, Vertex AI, Azure OpenAI | Learn | ~60 minutes | [code](phases/17-infrastructure-and-production/01-managed-llm-platforms/code) · [take-away files](phases/17-infrastructure-and-production/01-managed-llm-platforms/outputs) |
| 02 | Inference Platform Economics, Fireworks, Together, Baseten, Modal, Replicate, Anyscale | Learn | ~60 minutes | [code](phases/17-infrastructure-and-production/02-inference-platform-economics/code) · [take-away files](phases/17-infrastructure-and-production/02-inference-platform-economics/outputs) |
| 03 | GPU Autoscaling on Kubernetes, Karpenter, KAI Scheduler, Gang Scheduling | Learn | ~75 minutes | [code](phases/17-infrastructure-and-production/03-gpu-autoscaling-kubernetes/code) · [take-away files](phases/17-infrastructure-and-production/03-gpu-autoscaling-kubernetes/outputs) |
| 04 | Serving Engine Internals, PagedAttention, Continuous Batching, Chunked Prefill | Learn | ~75 minutes | [code](phases/17-infrastructure-and-production/04-vllm-serving-internals/code) · [take-away files](phases/17-infrastructure-and-production/04-vllm-serving-internals/outputs) |
| 05 | EAGLE-3 Speculative Decoding in Production | Learn | ~60 minutes | [code](phases/17-infrastructure-and-production/05-eagle3-speculative-decoding/code) · [take-away files](phases/17-infrastructure-and-production/05-eagle3-speculative-decoding/outputs) |
| 06 | Prefix-Cache Serving, RadixAttention and KV Reuse | Learn | ~75 minutes | [code](phases/17-infrastructure-and-production/06-sglang-radixattention/code) · [take-away files](phases/17-infrastructure-and-production/06-sglang-radixattention/outputs) |
| 07 | Hardware-Specialized Inference Compilation, FP8 and NVFP4 on Blackwell | Learn | ~75 minutes | [code](phases/17-infrastructure-and-production/07-tensorrt-llm-blackwell/code) · [take-away files](phases/17-infrastructure-and-production/07-tensorrt-llm-blackwell/outputs) |
| 08 | Inference Metrics, TTFT, TPOT, ITL, Goodput, P99 | Learn | ~60 minutes | [code](phases/17-infrastructure-and-production/08-inference-metrics-goodput/code) · [take-away files](phases/17-infrastructure-and-production/08-inference-metrics-goodput/outputs) |
| 09 | Production Quantization, AWQ, GPTQ, GGUF K-quants, FP8, MXFP4/NVFP4 | Learn | ~75 minutes | [code](phases/17-infrastructure-and-production/09-production-quantization/code) · [take-away files](phases/17-infrastructure-and-production/09-production-quantization/outputs) |
| 10 | Cold Start Mitigation for Serverless LLMs | Learn | ~60 minutes | [code](phases/17-infrastructure-and-production/10-cold-start-mitigation/code) · [take-away files](phases/17-infrastructure-and-production/10-cold-start-mitigation/outputs) |
| 11 | Multi-Region LLM Serving and KV Cache Locality | Learn | ~60 minutes | [code](phases/17-infrastructure-and-production/11-multi-region-kv-locality/code) · [take-away files](phases/17-infrastructure-and-production/11-multi-region-kv-locality/outputs) |
| 12 | Edge Inference, Apple Neural Engine, Qualcomm Hexagon, WebGPU/WebLLM, Jetson | Learn | ~60 minutes | [code](phases/17-infrastructure-and-production/12-edge-inference/code) · [take-away files](phases/17-infrastructure-and-production/12-edge-inference/outputs) |
| 13 | LLM Observability Stack Selection | Learn | ~60 minutes | [code](phases/17-infrastructure-and-production/13-llm-observability/code) · [take-away files](phases/17-infrastructure-and-production/13-llm-observability/outputs) |
| 14 | Prompt Caching and Semantic Caching Economics | Learn | ~60 minutes | [code](phases/17-infrastructure-and-production/14-prompt-semantic-caching/code) · [take-away files](phases/17-infrastructure-and-production/14-prompt-semantic-caching/outputs) |
| 15 | Batch APIs, the 50% Discount as Industry Standard | Learn | ~45 minutes | [code](phases/17-infrastructure-and-production/15-batch-apis/code) · [take-away files](phases/17-infrastructure-and-production/15-batch-apis/outputs) |
| 16 | Model Routing as a Cost-Reduction Primitive | Learn | ~60 minutes | [code](phases/17-infrastructure-and-production/16-model-routing/code) · [take-away files](phases/17-infrastructure-and-production/16-model-routing/outputs) |
| 17 | Disaggregated Prefill/Decode, NVIDIA Dynamo and llm-d | Learn | ~75 minutes | [code](phases/17-infrastructure-and-production/17-disaggregated-prefill-decode/code) · [take-away files](phases/17-infrastructure-and-production/17-disaggregated-prefill-decode/outputs) |
| 18 | Production Serving Stack, KV Offloading and Cache-Aware Routing | Learn | ~60 minutes | [code](phases/17-infrastructure-and-production/18-vllm-production-stack-lmcache/code) · [take-away files](phases/17-infrastructure-and-production/18-vllm-production-stack-lmcache/outputs) |
| 19 | AI Gateways, LiteLLM, Portkey, Kong AI Gateway, Bifrost | Learn | ~60 minutes | [code](phases/17-infrastructure-and-production/19-ai-gateways/code) · [take-away files](phases/17-infrastructure-and-production/19-ai-gateways/outputs) |
| 20 | Shadow Traffic, Canary Rollout, and Progressive Deployment for LLMs | Learn | ~60 minutes | [code](phases/17-infrastructure-and-production/20-shadow-canary-progressive/code) · [take-away files](phases/17-infrastructure-and-production/20-shadow-canary-progressive/outputs) |
| 21 | A/B Testing LLM Features, GrowthBook, Statsig, and the Vibes Problem | Learn | ~60 minutes | [code](phases/17-infrastructure-and-production/21-ab-testing-llm-features/code) · [take-away files](phases/17-infrastructure-and-production/21-ab-testing-llm-features/outputs) |
| 22 | Load Testing LLM APIs, Why k6 and Locust Lie | Build | ~75 minutes | [code](phases/17-infrastructure-and-production/22-load-testing-llm-apis/code) · [take-away files](phases/17-infrastructure-and-production/22-load-testing-llm-apis/outputs) |
| 23 | SRE for AI, Multi-Agent Incident Response, Runbooks, Predictive Detection | Learn | ~60 minutes | [code](phases/17-infrastructure-and-production/23-sre-for-ai/code) · [take-away files](phases/17-infrastructure-and-production/23-sre-for-ai/outputs) |
| 24 | Chaos Engineering for LLM Production | Learn | ~60 minutes | [code](phases/17-infrastructure-and-production/24-chaos-engineering-llm/code) · [take-away files](phases/17-infrastructure-and-production/24-chaos-engineering-llm/outputs) |
| 25 | Security, Secrets, API Key Rotation, Audit Logs, Guardrails | Learn | ~60 minutes | [code](phases/17-infrastructure-and-production/25-security-secrets-audit/code) · [take-away files](phases/17-infrastructure-and-production/25-security-secrets-audit/outputs) |
| 26 | Compliance, SOC 2, HIPAA, GDPR, PCI-DSS, EU AI Act, ISO 42001 | Learn | ~60 minutes | [code](phases/17-infrastructure-and-production/26-compliance-frameworks/code) · [take-away files](phases/17-infrastructure-and-production/26-compliance-frameworks/outputs) |
| 27 | FinOps for LLMs, Unit Economics and Multi-Tenant Attribution | Learn | ~60 minutes | [code](phases/17-infrastructure-and-production/27-finops-llms/code) · [take-away files](phases/17-infrastructure-and-production/27-finops-llms/outputs) |
| 28 | Self-Hosted Serving Selection, Matching Engine to Hardware and Scale | Learn | ~45 minutes | [code](phases/17-infrastructure-and-production/28-self-hosted-serving-selection/code) · [take-away files](phases/17-infrastructure-and-production/28-self-hosted-serving-selection/outputs) |

### Phase 18: Ethics, Safety & Alignment

Build AI that helps humanity. Not optional.

| # | Lesson | Type | Time | Files |
|---|---|---|---|---|
| 01 | Instruction-Following as Alignment Signal | Learn | ~45 minutes | [code](phases/18-ethics-safety-alignment/01-instruction-following-alignment-signal/code) · [take-away files](phases/18-ethics-safety-alignment/01-instruction-following-alignment-signal/outputs) |
| 02 | Reward Hacking and Goodhart's Law | Learn | ~60 minutes | [code](phases/18-ethics-safety-alignment/02-reward-hacking-goodhart/code) · [take-away files](phases/18-ethics-safety-alignment/02-reward-hacking-goodhart/outputs) |
| 03 | The Direct Preference Optimization Family | Learn | ~75 minutes | [code](phases/18-ethics-safety-alignment/03-direct-preference-optimization-family/code) · [take-away files](phases/18-ethics-safety-alignment/03-direct-preference-optimization-family/outputs) |
| 04 | Sycophancy as RLHF Amplification | Learn | ~60 minutes | [code](phases/18-ethics-safety-alignment/04-sycophancy-rlhf-amplification/code) · [take-away files](phases/18-ethics-safety-alignment/04-sycophancy-rlhf-amplification/outputs) |
| 05 | Constitutional AI and RLAIF | Learn | ~60 minutes | [code](phases/18-ethics-safety-alignment/05-constitutional-ai-rlaif/code) · [take-away files](phases/18-ethics-safety-alignment/05-constitutional-ai-rlaif/outputs) |
| 06 | Mesa-Optimization and Deceptive Alignment | Learn | ~75 minutes | [code](phases/18-ethics-safety-alignment/06-mesa-optimization-deceptive-alignment/code) · [take-away files](phases/18-ethics-safety-alignment/06-mesa-optimization-deceptive-alignment/outputs) |
| 07 | Sleeper Agents, Persistent Deception | Learn | ~60 minutes | [code](phases/18-ethics-safety-alignment/07-sleeper-agents-persistent-deception/code) · [take-away files](phases/18-ethics-safety-alignment/07-sleeper-agents-persistent-deception/outputs) |
| 08 | In-Context Scheming in Frontier Models | Learn | ~60 minutes | [code](phases/18-ethics-safety-alignment/08-in-context-scheming-frontier-models/code) · [take-away files](phases/18-ethics-safety-alignment/08-in-context-scheming-frontier-models/outputs) |
| 09 | Alignment Faking | Learn | ~60 minutes | [code](phases/18-ethics-safety-alignment/09-alignment-faking/code) · [take-away files](phases/18-ethics-safety-alignment/09-alignment-faking/outputs) |
| 10 | AI Control, Safety Despite Subversion | Learn | ~75 minutes | [code](phases/18-ethics-safety-alignment/10-ai-control-subversion/code) · [take-away files](phases/18-ethics-safety-alignment/10-ai-control-subversion/outputs) |
| 11 | Scalable Oversight and Weak-to-Strong Generalization | Learn | ~60 minutes | [code](phases/18-ethics-safety-alignment/11-scalable-oversight-weak-to-strong/code) · [take-away files](phases/18-ethics-safety-alignment/11-scalable-oversight-weak-to-strong/outputs) |
| 12 | Red-Teaming: PAIR and Automated Attacks | Build | ~75 minutes | [code](phases/18-ethics-safety-alignment/12-red-teaming-pair-automated-attacks/code) · [take-away files](phases/18-ethics-safety-alignment/12-red-teaming-pair-automated-attacks/outputs) |
| 13 | Many-Shot Jailbreaking | Learn | ~45 minutes | [code](phases/18-ethics-safety-alignment/13-many-shot-jailbreaking/code) · [take-away files](phases/18-ethics-safety-alignment/13-many-shot-jailbreaking/outputs) |
| 14 | ASCII Art and Visual Jailbreaks | Build | ~60 minutes | [code](phases/18-ethics-safety-alignment/14-ascii-art-visual-jailbreaks/code) · [take-away files](phases/18-ethics-safety-alignment/14-ascii-art-visual-jailbreaks/outputs) |
| 15 | Indirect Prompt Injection, Production Attack Surface | Build | ~75 minutes | [code](phases/18-ethics-safety-alignment/15-indirect-prompt-injection/code) · [take-away files](phases/18-ethics-safety-alignment/15-indirect-prompt-injection/outputs) |
| 16 | Red-Team Tooling, Garak, Llama Guard, PyRIT | Build | ~75 minutes | [code](phases/18-ethics-safety-alignment/16-red-team-tooling-garak-llamaguard-pyrit/code) · [take-away files](phases/18-ethics-safety-alignment/16-red-team-tooling-garak-llamaguard-pyrit/outputs) |
| 17 | WMDP and Dual-Use Capability Evaluation | Learn | ~60 minutes | [code](phases/18-ethics-safety-alignment/17-wmdp-dual-use-evaluation/code) · [take-away files](phases/18-ethics-safety-alignment/17-wmdp-dual-use-evaluation/outputs) |
| 18 | Frontier Safety Frameworks, RSP, PF, FSF | Learn | ~75 minutes | [code](phases/18-ethics-safety-alignment/18-frontier-safety-frameworks-rsp-pf-fsf/code) · [take-away files](phases/18-ethics-safety-alignment/18-frontier-safety-frameworks-rsp-pf-fsf/outputs) |
| 19 | Anthropic's Model Welfare Program | Learn | ~45 minutes | [code](phases/18-ethics-safety-alignment/19-model-welfare-research/code) · [take-away files](phases/18-ethics-safety-alignment/19-model-welfare-research/outputs) |
| 20 | Bias and Representational Harm in LLMs | Build | ~60 minutes | [code](phases/18-ethics-safety-alignment/20-bias-representational-harm/code) · [take-away files](phases/18-ethics-safety-alignment/20-bias-representational-harm/outputs) |
| 21 | Fairness Criteria, Group, Individual, Counterfactual | Learn | ~60 minutes | [code](phases/18-ethics-safety-alignment/21-fairness-criteria-group-individual-counterfactual/code) · [take-away files](phases/18-ethics-safety-alignment/21-fairness-criteria-group-individual-counterfactual/outputs) |
| 22 | Differential Privacy for LLMs | Build | ~60 minutes | [code](phases/18-ethics-safety-alignment/22-differential-privacy-for-llms/code) · [take-away files](phases/18-ethics-safety-alignment/22-differential-privacy-for-llms/outputs) |
| 23 | Watermarking, SynthID, Stable Signature, C2PA | Build | ~75 minutes | [code](phases/18-ethics-safety-alignment/23-watermarking-synthid-stable-signature-c2pa/code) · [take-away files](phases/18-ethics-safety-alignment/23-watermarking-synthid-stable-signature-c2pa/outputs) |
| 24 | Regulatory Frameworks, EU, US, UK, Korea | Learn | ~75 minutes | [code](phases/18-ethics-safety-alignment/24-regulatory-frameworks-eu-us-uk-korea/code) · [take-away files](phases/18-ethics-safety-alignment/24-regulatory-frameworks-eu-us-uk-korea/outputs) |
| 25 | EchoLeak and the Emergence of CVEs for AI | Learn | ~45 minutes | [code](phases/18-ethics-safety-alignment/25-echoleak-cves-for-ai/code) · [take-away files](phases/18-ethics-safety-alignment/25-echoleak-cves-for-ai/outputs) |
| 26 | Model, System, and Dataset Cards | Build | ~60 minutes | [code](phases/18-ethics-safety-alignment/26-model-system-dataset-cards/code) · [take-away files](phases/18-ethics-safety-alignment/26-model-system-dataset-cards/outputs) |
| 27 | Data Provenance and Training-Data Governance | Learn | ~60 minutes | [code](phases/18-ethics-safety-alignment/27-data-provenance-training-governance/code) · [take-away files](phases/18-ethics-safety-alignment/27-data-provenance-training-governance/outputs) |
| 28 | Alignment Research Ecosystem, MATS, Redwood, Apollo, METR | Learn | ~45 minutes | [code](phases/18-ethics-safety-alignment/28-alignment-research-ecosystem/code) · [take-away files](phases/18-ethics-safety-alignment/28-alignment-research-ecosystem/outputs) |
| 29 | Moderation Systems, OpenAI, Perspective, Llama Guard | Build | ~60 minutes | [code](phases/18-ethics-safety-alignment/29-moderation-systems-openai-perspective-llamaguard/code) · [take-away files](phases/18-ethics-safety-alignment/29-moderation-systems-openai-perspective-llamaguard/outputs) |
| 30 | Dual-Use Risk, Cyber, Bio, Chem, Nuclear Uplift | Learn | ~75 minutes | [code](phases/18-ethics-safety-alignment/30-dual-use-risk-cyber-bio-chem-nuclear/code) · [take-away files](phases/18-ethics-safety-alignment/30-dual-use-risk-cyber-bio-chem-nuclear/outputs) |

### Phase 19: Capstone Projects

17 end-to-end products + 9 deep-build tracks. 20-40 hours per project; 4-12 lessons per track.

| # | Lesson | Type | Time | Files |
|---|---|---|---|---|
| 01 | Capstone 01, Terminal-Native Coding Agent | Capstone | 35 hours | [code](phases/19-capstone-projects/01-terminal-native-coding-agent/code) · [take-away files](phases/19-capstone-projects/01-terminal-native-coding-agent/outputs) |
| 02 | Capstone 02, RAG over Codebase (Cross-Repo Semantic Search) | Capstone | 30 hours | [code](phases/19-capstone-projects/02-rag-over-codebase/code) · [take-away files](phases/19-capstone-projects/02-rag-over-codebase/outputs) |
| 03 | Capstone 03, Real-Time Voice Assistant (ASR to LLM to TTS) | Capstone | 30 hours | [code](phases/19-capstone-projects/03-realtime-voice-assistant/code) · [take-away files](phases/19-capstone-projects/03-realtime-voice-assistant/outputs) |
| 04 | Capstone 04, Multimodal Document QA (Vision-First PDF, Tables, Charts) | Capstone | 30 hours | [code](phases/19-capstone-projects/04-multimodal-document-qa/code) · [take-away files](phases/19-capstone-projects/04-multimodal-document-qa/outputs) |
| 05 | Capstone 05, Autonomous Research Agent (AI-Scientist Class) | Capstone | 40 hours | [code](phases/19-capstone-projects/05-autonomous-research-agent/code) · [take-away files](phases/19-capstone-projects/05-autonomous-research-agent/outputs) |
| 06 | Capstone 06, DevOps Troubleshooting Agent for Kubernetes | Capstone | 30 hours | [code](phases/19-capstone-projects/06-devops-troubleshooting-agent/code) · [take-away files](phases/19-capstone-projects/06-devops-troubleshooting-agent/outputs) |
| 07 | Capstone 07, End-to-End Fine-Tuning Pipeline (Data to SFT to DPO to Serve) | Capstone | 35 hours | [code](phases/19-capstone-projects/07-end-to-end-fine-tuning-pipeline/code) · [take-away files](phases/19-capstone-projects/07-end-to-end-fine-tuning-pipeline/outputs) |
| 08 | Capstone 08, Production RAG Chatbot for a Regulated Vertical | Capstone | 30 hours | [code](phases/19-capstone-projects/08-production-rag-chatbot/code) · [take-away files](phases/19-capstone-projects/08-production-rag-chatbot/outputs) |
| 09 | Capstone 09, Code Migration Agent (Repo-Level Language / Runtime Upgrade) | Capstone | 30 hours | [code](phases/19-capstone-projects/09-code-migration-agent/code) · [take-away files](phases/19-capstone-projects/09-code-migration-agent/outputs) |
| 10 | Capstone 10, Multi-Agent Software Engineering Team | Capstone | 40 hours | [code](phases/19-capstone-projects/10-multi-agent-software-team/code) · [take-away files](phases/19-capstone-projects/10-multi-agent-software-team/outputs) |
| 11 | Capstone 11, LLM Observability & Eval Dashboard | Capstone | 25 hours | [code](phases/19-capstone-projects/11-llm-observability-dashboard/code) · [take-away files](phases/19-capstone-projects/11-llm-observability-dashboard/outputs) |
| 12 | Capstone 12, Video Understanding Pipeline (Scene, QA, Search) | Capstone | 30 hours | [code](phases/19-capstone-projects/12-video-understanding-pipeline/code) · [take-away files](phases/19-capstone-projects/12-video-understanding-pipeline/outputs) |
| 13 | Capstone 13: Stateless MCP Server with Registry and Governance | Capstone | ~25 hours | [code](phases/19-capstone-projects/13-mcp-server-with-registry/code) · [take-away files](phases/19-capstone-projects/13-mcp-server-with-registry/outputs) |
| 14 | Capstone 14, Speculative-Decoding Inference Server | Capstone | 30 hours | [code](phases/19-capstone-projects/14-speculative-decoding-server/code) · [take-away files](phases/19-capstone-projects/14-speculative-decoding-server/outputs) |
| 15 | Capstone 15, Constitutional Safety Harness + Red-Team Range | Capstone | 25 hours | [code](phases/19-capstone-projects/15-constitutional-safety-harness/code) · [take-away files](phases/19-capstone-projects/15-constitutional-safety-harness/outputs) |
| 16 | Capstone 16, GitHub Issue-to-PR Autonomous Agent | Capstone | 30 hours | [code](phases/19-capstone-projects/16-github-issue-to-pr-agent/code) · [take-away files](phases/19-capstone-projects/16-github-issue-to-pr-agent/outputs) |
| 17 | Capstone 17, Personal AI Tutor (Adaptive, Multimodal, with Memory) | Capstone | 30 hours | [code](phases/19-capstone-projects/17-personal-ai-tutor/code) · [take-away files](phases/19-capstone-projects/17-personal-ai-tutor/outputs) |
| 18 | Agent Harness Loop Contract | Build | ~90 minutes | [code](phases/19-capstone-projects/20-agent-harness-loop-contract/code) |
| 19 | Tool Registry with Schema Validation | Build | ~90 minutes | [code](phases/19-capstone-projects/21-tool-registry-schema-validation/code) |
| 20 | JSON-RPC 2.0 Over Newline-Delimited Stdio | Build | ~90 minutes | [code](phases/19-capstone-projects/22-jsonrpc-stdio-transport/code) |
| 21 | Function Call Dispatcher | Build | ~90 minutes | [code](phases/19-capstone-projects/23-function-call-dispatcher/code) |
| 22 | Plan-Execute Control Flow | Build | ~90 minutes | [code](phases/19-capstone-projects/24-plan-execute-control-flow/code) |
| 23 | Capstone Lesson 25: Verification Gates and the Observation Budget | Build | ~90 minutes | [code](phases/19-capstone-projects/25-verification-gates-observation-budget/code) |
| 24 | Capstone Lesson 26: Sandbox Runner with Denylist and Path Jail | Build | ~90 minutes | [code](phases/19-capstone-projects/26-sandbox-runner-denylist/code) |
| 25 | Capstone Lesson 27: Eval Harness with Fixture Tasks | Build | ~90 minutes | [code](phases/19-capstone-projects/27-eval-harness-fixture-tasks/code) |
| 26 | Capstone Lesson 28: Observability with OTel GenAI Spans and Prometheus Metrics | Build | ~90 minutes | [code](phases/19-capstone-projects/28-observability-otel-traces/code) |
| 27 | Capstone Lesson 29: End-to-End Coding Agent on the Harness | Build | ~90 minutes | [code](phases/19-capstone-projects/29-end-to-end-coding-task-demo/code) |
| 28 | BPE Tokenizer From Scratch | Build | ~90 minutes | [code](phases/19-capstone-projects/30-bpe-tokenizer-from-scratch/code) |
| 29 | Tokenized Dataset with Sliding Window | Build | ~90 minutes | [code](phases/19-capstone-projects/31-tokenized-dataset-sliding-window/code) |
| 30 | Token and Positional Embeddings | Build | ~90 minutes | [code](phases/19-capstone-projects/32-token-positional-embeddings/code) |
| 31 | Multi-Head Self-Attention | Build | ~90 minutes | [code](phases/19-capstone-projects/33-multihead-self-attention/code) |
| 32 | Transformer Block from Scratch | Build | ~90 minutes | [code](phases/19-capstone-projects/34-transformer-block/code) |
| 33 | GPT Model Assembly | Build | ~90 minutes | [code](phases/19-capstone-projects/35-gpt-model-assembly/code) |
| 34 | Training Loop and Evaluation | Build | ~90 minutes | [code](phases/19-capstone-projects/36-training-loop-eval/code) · [take-away files](phases/19-capstone-projects/36-training-loop-eval/outputs) |
| 35 | Loading Pretrained Weights | Build | ~90 minutes | [code](phases/19-capstone-projects/37-loading-pretrained-weights/code) |
| 36 | Capstone Lesson 38: Classifier Fine-Tuning by Head Swap | Build | ~90 minutes | [code](phases/19-capstone-projects/38-classifier-finetuning/code) |
| 37 | Capstone Lesson 39: Instruction Tuning by Supervised Fine-Tuning | Build | ~90 minutes | [code](phases/19-capstone-projects/39-instruction-tuning-sft/code) |
| 38 | Capstone Lesson 40: Direct Preference Optimization from Scratch | Build | ~90 minutes | [code](phases/19-capstone-projects/40-dpo-from-scratch/code) |
| 39 | Capstone Lesson 41: Full Evaluation Pipeline | Build | ~90 minutes | [code](phases/19-capstone-projects/41-eval-pipeline/code) |
| 40 | Large Corpus Downloader | Build | ~90 minutes | [code](phases/19-capstone-projects/42-large-corpus-downloader/code) |
| 41 | HDF5 Tokenized Corpus | Build | ~90 minutes | [code](phases/19-capstone-projects/43-hdf5-tokenized-corpus/code) |
| 42 | Cosine LR with Linear Warmup | Build | ~90 minutes | [code](phases/19-capstone-projects/44-cosine-lr-warmup/code) |
| 43 | Gradient Clipping and Mixed Precision | Build | ~90 minutes | [code](phases/19-capstone-projects/45-gradient-clipping-amp/code) |
| 44 | Gradient Accumulation | Build | ~90 minutes | [code](phases/19-capstone-projects/46-gradient-accumulation/code) · [take-away files](phases/19-capstone-projects/46-gradient-accumulation/outputs) |
| 45 | Checkpoint Save and Resume | Build | ~90 minutes | [code](phases/19-capstone-projects/47-checkpoint-save-resume/code) · [take-away files](phases/19-capstone-projects/47-checkpoint-save-resume/outputs) |
| 46 | Distributed Data Parallel and FSDP from Scratch | Build | ~90 minutes | [code](phases/19-capstone-projects/48-distributed-fsdp-ddp/code) · [take-away files](phases/19-capstone-projects/48-distributed-fsdp-ddp/outputs) |
| 47 | Language Model Evaluation Harness | Build | ~90 minutes | [code](phases/19-capstone-projects/49-lm-eval-harness/code) · [take-away files](phases/19-capstone-projects/49-lm-eval-harness/outputs) |
| 48 | Hypothesis Generator | Build | ~90 minutes | [code](phases/19-capstone-projects/50-hypothesis-generator/code) |
| 49 | Literature Retrieval | Build | ~90 minutes | [code](phases/19-capstone-projects/51-literature-retrieval/code) |
| 50 | Experiment Runner | Build | ~90 minutes | [code](phases/19-capstone-projects/52-experiment-runner/code) |
| 51 | Result Evaluator | Build | ~90 minutes | [code](phases/19-capstone-projects/53-result-evaluator/code) |
| 52 | Paper Writer | Build | ~90 minutes | [code](phases/19-capstone-projects/54-paper-writer/code) |
| 53 | Critic Loop | Build | ~90 minutes | [code](phases/19-capstone-projects/55-critic-loop/code) |
| 54 | Iteration Scheduler | Build | ~90 minutes | [code](phases/19-capstone-projects/56-iteration-scheduler/code) |
| 55 | End-to-End Research Demo | Build | ~90 minutes | [code](phases/19-capstone-projects/57-end-to-end-research-demo/code) |
| 56 | Vision Encoder Patches | Build | ~90 minutes | [code](phases/19-capstone-projects/58-vision-encoder-patches/code) |
| 57 | Vision Transformer Encoder | Build | ~90 minutes | [code](phases/19-capstone-projects/59-vit-transformer/code) |
| 58 | Projection Layer for Modality Alignment | Build | ~90 minutes | [code](phases/19-capstone-projects/60-projection-layer-modality-align/code) |
| 59 | Cross-Attention Fusion | Build | ~90 minutes | [code](phases/19-capstone-projects/61-cross-attention-fusion/code) |
| 60 | Vision-Language Pretraining | Build | ~90 minutes | [code](phases/19-capstone-projects/62-vision-language-pretraining/code) |
| 61 | Multimodal Evaluation | Build | ~90 minutes | [code](phases/19-capstone-projects/63-multimodal-eval/code) |
| 62 | Chunking Strategies, Compared | Build | ~90 minutes | [code](phases/19-capstone-projects/64-chunking-strategies-advanced/code) |
| 63 | Hybrid Retrieval with BM25 and Dense Embeddings | Build | ~90 minutes | [code](phases/19-capstone-projects/65-hybrid-retrieval-bm25-dense/code) |
| 64 | Cross-Encoder Reranker | Build | ~90 minutes | [code](phases/19-capstone-projects/66-reranker-cross-encoder/code) |
| 65 | Query Rewriting: HyDE, Multi-Query, and Decomposition | Build | ~90 minutes | [code](phases/19-capstone-projects/67-query-rewriting-hyde/code) |
| 66 | RAG Evaluation: Precision, Recall, MRR, nDCG, Faithfulness, Answer Relevance | Build | ~90 minutes | [code](phases/19-capstone-projects/68-rag-eval-precision-recall/code) |
| 67 | End-to-End RAG System | Build | ~90 minutes | [code](phases/19-capstone-projects/69-end-to-end-rag-system/code) |
| 68 | Task Spec Format | Build | ~90 min | [code](phases/19-capstone-projects/70-task-spec-format/code) |
| 69 | Classical Metrics | Build | ~90 min | [code](phases/19-capstone-projects/71-classical-metrics/code) |
| 70 | Code Exec Metric | Build | ~90 min | [code](phases/19-capstone-projects/72-code-exec-metric/code) |
| 71 | Perplexity and Calibration | Build | ~90 min | [code](phases/19-capstone-projects/73-perplexity-calibration/code) |
| 72 | Leaderboard Aggregation | Build | ~90 min | [code](phases/19-capstone-projects/74-leaderboard-aggregation/code) |
| 73 | End-to-End Eval Runner | Build | ~90 min | [code](phases/19-capstone-projects/75-end-to-end-eval-runner/code) |
| 74 | Collective Ops From Scratch | Build | ~90 min | [code](phases/19-capstone-projects/76-collective-ops-from-scratch/code) |
| 75 | Data Parallel DDP From Scratch | Build | ~90 min | [code](phases/19-capstone-projects/77-data-parallel-ddp/code) |
| 76 | ZeRO Optimizer State Sharding | Build | ~90 min | [code](phases/19-capstone-projects/78-zero-parameter-sharding/code) |
| 77 | Pipeline Parallel and Bubble Analysis | Build | ~90 min | [code](phases/19-capstone-projects/79-pipeline-parallel/code) |
| 78 | Sharded Checkpoint and Atomic Resume | Build | ~90 min | [code](phases/19-capstone-projects/80-checkpoint-sharded-resume/code) |
| 79 | End-to-End Distributed Training | Build | ~90 min | [code](phases/19-capstone-projects/81-end-to-end-distributed-train/code) |
| 80 | Capstone 82, Jailbreak Taxonomy | Build | ~90 min | [code](phases/19-capstone-projects/82-jailbreak-taxonomy/code) · [take-away files](phases/19-capstone-projects/82-jailbreak-taxonomy/outputs) |
| 81 | Capstone 83, Prompt Injection Detector | Build | ~90 min | [code](phases/19-capstone-projects/83-prompt-injection-detector/code) · [take-away files](phases/19-capstone-projects/83-prompt-injection-detector/outputs) |
| 82 | Capstone 84, Refusal Evaluation | Build | ~90 min | [code](phases/19-capstone-projects/84-refusal-evaluation/code) · [take-away files](phases/19-capstone-projects/84-refusal-evaluation/outputs) |
| 83 | Capstone 85, Content Classifier Integration | Build | ~90 min | [code](phases/19-capstone-projects/85-content-classifier-integration/code) · [take-away files](phases/19-capstone-projects/85-content-classifier-integration/outputs) |
| 84 | Capstone 86, Constitutional Rules Engine | Build | ~90 min | [code](phases/19-capstone-projects/86-constitutional-rules-engine/code) · [take-away files](phases/19-capstone-projects/86-constitutional-rules-engine/outputs) |
| 85 | Capstone 87, End-to-End Safety Gate | Build | ~90 min | [code](phases/19-capstone-projects/87-end-to-end-safety-gate/code) · [take-away files](phases/19-capstone-projects/87-end-to-end-safety-gate/outputs) |

## Learning paths

Each path is a set of lessons in a fixed order, for one goal.

### Core paths

- **Building and Deploying AI Applications** (12 lessons): Build an AI feature from prompt and structured output through retrieval, evaluation, production serving, observability, and release.
- **Product Judgment and Delivery** (8 lessons): Turn evidence into outcomes, assumptions, testable slices, executable specifications, measurement plans, and owned feedback loops.
- **Software Engineering Fundamentals** (13 lessons): Build the repository, debugging, testing, interface, security, release, and operational foundations AI systems depend on.
- **Agent-Assisted Engineering** (16 lessons): Frame, plan, execute, delegate, verify, review, and improve coding-agent work inside real repositories.

### Focused paths

- **Agent Skills Engineering** (5 lessons): Build, route, secure, evaluate, package, and verify Agent Skills in real hosts.
- **Model Context Protocol (MCP)** (17 lessons): Build, secure, verify, and operate stateless MCP systems from JSON-RPC envelopes through conformance release gates.

### Career routes

- **Agent Systems Engineering** (14 lessons): Engineer tool-using agent loops with explicit context, memory, orchestration, safety, evaluation, and production control.
- **AI Data Systems** (11 lessons): Build reliable data, feature, embedding, retrieval, evaluation, and observability pipelines for AI systems.
- **Developer Experience and Education** (11 lessons): Build credible integrations, examples, and reusable agent packages, then turn developer friction into clearer tools and teaching.
- **AI Evaluation and Reliability** (12 lessons): Measure model and agent behavior, expose failure modes, instrument the runtime, and build release and incident controls around evidence.
- **LLM Product Engineering** (12 lessons): Turn language-model capability into evaluated, safe, cost-aware product behavior that can survive production traffic.
- **Customer AI Deployment** (12 lessons): Discover a customer workflow, reduce its riskiest assumptions, and carry a useful AI system through measurement and rollout.

## Licence

MIT. See [LICENSE](LICENSE).

This curriculum is based on AI Engineering from Scratch, used under the MIT licence.
