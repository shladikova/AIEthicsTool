---
cover: >-
  https://images.unsplash.com/photo-1460925895917-afdab827c52f?crop=entropy&cs=srgb&fm=jpg&ixid=M3wxOTcwMjR8MHwxfHNlYXJjaHw0fHxhbmFseXNpc3xlbnwwfHx8fDE3MDAwMTI1OTN8MA&ixlib=rb-4.0.3&q=85
coverY: 0
layout:
  cover:
    visible: true
    size: full
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# 🏋♀ Training

In the training phase datasets are obtained to train and test the algorithms. In this phase there are several ethical issues related to the preparation and training of data. The team should review the guidelines provided below.



### Dataset Preparation

The origin of the data should be well documented.

The quality of the data should be appropriate (e.g. missing values, errors, etc).

The data should be relevant for the project.

The Data should be aligned with FAIR Principles.

{% hint style="info" %}
**FAIR Principles Definition**

The FAIR principles (Findable, Accessible, Interoperable, and Reusable) are a set of guiding principles for making data discoverable and understandable by both humans and computers. These principles help improve the quality and utility of data in research and data-driven decision-making.
{% endhint %}

Data should be aligned with CARE Principles for Indigenous Data Governance.

{% hint style="info" %}
**CARE Principles Definition**

The CARE Principles are a set of guiding principles for Indigenous Data Governance. CARE stands for "Collective Benefit," "Authority to Control," "Responsibility," and "Ethics." These principles emphasize the importance of respecting Indigenous rights and well-being and ensuring that Indigenous communities have control over data that concerns them.
{% endhint %}

***

### Model Selection

<details>

<summary>Performance should not be the only factor in choosing the model.</summary>

* Instrument the system for measurement, documenting, and tracking, e.g., by maintaining histories, audit logs and other information&#x20;
* Measure and document human oversight of AI systems.&#x20;
* Document the degree of oversight that is provided by specified AI actors (end users, third-party providers...) regarding the AI system output.&#x20;
* Document statistics about downstream actions by end users and operators such as system overrides, reported errors or complaints, time to respond, and response types.&#x20;
* Track, document, and measure organizational accountability regarding AI systems via policy exceptions and escalations, and document decisions made by accountable parties.&#x20;
* Track and audit the effectiveness of organizational mechanisms related to AI risk management, including:&#x20;
  * Lines of communication between AI actors, executive leadership, users and impacted communities.&#x20;
  * Roles and responsibilities for AI actors and executive leadership.&#x20;
  * Organizational accountability roles, e.g., chief model risk officers, AI oversight committees, responsible or ethical AI directors, etc.&#x20;

</details>

<details>

<summary>Explainable model should be preferred over opaque/black box models.</summary>

* When possible or available, utilize approaches that are inherently explainable, such as traditional and penalized generalized linear models, decision trees, nearest-neighbor and prototype-based approaches, rule-based models, generalized additive models, explainable boosting machines and neural additive models.&#x20;
* Test explanation methods and resulting explanations prior to deployment to gain feedback from relevant stakeholders, including potentially impacted individuals or groups about whether explanations are accurate, clear, and understandable.&#x20;
* Document AI model details including model type (e.g., convolutional neural network, reinforcement learning, decision tree, random forest, etc.) data features, training algorithms, proposed uses, decision thresholds, training data, evaluation data, and ethical considerations.&#x20;
* Establish, document, and report performance and error metrics across demographic groups and other segments relevant to the deployment context.&#x20;
* Explain systems using a variety of methods, e.g., visualizations, model extraction, feature importance, and others. Since explanations may not accurately summarize complex systems, test explanations according to properties such as fidelity, consistency, robustness, and interpretability.&#x20;
* Test the quality of system explanations with end-users and other groups.&#x20;
* Secure model development processes to avoid vulnerability to external manipulation such as gaming explanation processes.&#x20;
* Test for changes in models over time, including for models that adjust in response to production data.&#x20;

</details>

<details>

<summary>Excessive environmental costs should be avoided when training a model.</summary>

* Include environmental impact indicators in AI system design and development plans, including reducing consumption and improving efficiencies.&#x20;
* Identify, establish, and implement key indicators of AI system energy and water consumption and efficiency, and/or Greenhouse gases (GHG), along with actions to be taken if indicators rise above acceptable levels.&#x20;
* Establish measurable baselines for sustainable AI system operation in accordance with organizational policies, regulatory compliance, legal frameworks, and environmental protection and sustainability norms.&#x20;
* Assess tradeoffs between AI system performance and sustainable operations in accordance with organizational principles and policies, regulatory compliance, legal frameworks, and environmental protection and sustainability norms.&#x20;
* Estimate AI system emissions levels throughout the AI lifecycle via carbon calculators or similar process.&#x20;

</details>

***

### Training & Validation

The training process should be transparent.

Training phase should be properly documented.

The documentation should be available to the team.
