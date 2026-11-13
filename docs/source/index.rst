PyKEEN
======

PyKEEN helps you learn embeddings from knowledge graphs: collections of facts represented as ``(head, relation, tail)``
triples. These embeddings can help you rank missing links, compare models, or use the learned representations in other
machine learning tasks.

What can I do with PyKEEN?
--------------------------

- **Predict missing links.** Rank candidate entities for an incomplete triple, or score candidate triples, with a
  trained model. See :doc:`reference/predict`.
- **Compare knowledge graph embedding models.** Train and evaluate models on the same dataset, with explicit choices
  about candidate entities and filtering. See :doc:`explanation/understanding_evaluation`.
- **Reuse learned representations.** Export entity and relation embeddings for tasks such as clustering, regression, or
  classification. See :doc:`tutorial/first_steps`.
- **Work with your own knowledge graph.** Load triples from your data and construct training, validation, and test
  splits. See :doc:`howto/bring_your_own_data`.

Getting Started
---------------

.. automodule:: pykeen

This documentation is organized following the `Diátaxis <https://diataxis.fr/>`_ framework, which distinguishes between
four kinds of content: learning-oriented *tutorials*, goal-oriented *how-to guides*, understanding-oriented
*explanations*, and information-oriented *reference* material.

.. toctree::
    :caption: Tutorials
    :name: quickstart
    :maxdepth: 2

    installation
    tutorial/first_steps
    tutorial/translational_toy_example
    tutorial/inductive_lp

.. toctree::
    :caption: How-to Guides
    :name: howto
    :maxdepth: 2

    howto/bring_your_own_data
    howto/bring_your_own_interaction
    howto/extending_datasets
    howto/extending_models
    howto/splitting
    howto/node_piece
    howto/using_resolvers
    howto/checkpoints
    howto/running_hpo
    howto/running_ablation
    howto/trackers/index
    howto/troubleshooting

.. toctree::
    :caption: Explanation
    :name: explanation
    :maxdepth: 2

    explanation/models
    explanation/interactions
    explanation/representations
    explanation/normalizer_constrainer_regularizer
    explanation/understanding_evaluation
    explanation/performance
    explanation/dataset_degree_distributions

.. toctree::
    :caption: Reference
    :name: reference
    :maxdepth: 2

    reference/pipeline
    reference/models
    reference/datasets
    reference/triples
    reference/inverse
    reference/training
    reference/stoppers
    reference/losses
    reference/loss_weighting
    reference/regularizers
    reference/trackers
    reference/negative_sampling
    reference/optimizers
    reference/evaluation
    reference/metrics
    reference/hpo
    reference/ablation
    reference/predict
    reference/uncertainty
    reference/sealant
    reference/constants
    reference/checkpoints
    reference/nn/index
    reference/lightning
    reference/utils

.. toctree::
    :caption: Appendix
    :name: appendix
    :maxdepth: 2

    references

Indices and Tables
------------------

- :ref:`genindex`
- :ref:`modindex`
- :ref:`search`
