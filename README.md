## Neural Additive Models: Interpretable Machine Learning with Neural Nets

This repository contains open-source code  for NAMs.

<img src="https://i.imgur.com/Hvb7sb2.jpg" width="50%" alt="Neural Additive Model" >

Currently,
we release the `tf.keras.Model` for NAM which can be simply plugged into any neural network training procedure. We also provide helpers for
building a computation graph using NAM for classification/regression problems with `tf.compat.v1`.
The `nam_train.py` file provides the example of a training script on a single
dataset split.

Use `./run.sh` test script to ensure that the setup is correct.

## Dependencies

The code was tested under Ubuntu 16 and uses these packages:

- tensorflow>=1.15
- numpy>=1.15.2
- sklearn>=0.23
- pandas>=0.24
- absl-py

---

*Disclaimer about COMPAS dataset: It is important to note that
developing a machine learning model to predict pre-trial detention has a
number of important ethical considerations. You can learn more about these
issues in the Partnership on AI
[Report on Algorithmic Risk Assessment Tools in the U.S. Criminal Justice System](https://www.partnershiponai.org/report-on-machine-learning-in-risk-assessment-tools-in-the-u-s-criminal-justice-system/).
The Partnership on AI is a multi-stakeholder organization -- of which Google
is a member -- that creates guidelines around AI.*

*We’re using the COMPAS dataset only as an example of how to identify and
remediate fairness concerns in data. This dataset is canonical in the
algorithmic fairness literature.*
