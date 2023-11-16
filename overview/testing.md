---
cover: >-
  https://images.unsplash.com/photo-1600267147646-33cf514b5f3e?crop=entropy&cs=srgb&fm=jpg&ixid=M3wxOTcwMjR8MHwxfHNlYXJjaHw3fHx0ZXN0aW5nfGVufDB8fHx8MTcwMDAxMzgyNnww&ixlib=rb-4.0.3&q=85
coverY: 0
---

# 📊 Testing

In this phase the algorithm is tested. The team should follow procedures to evaluate the trustworthiness of the algorithm.

### :gear:Performance

{% hint style="info" %}
#### **Definition**

AI system performance or assurance criteria are measured qualitatively or quantitatively and demonstrated for conditions similar to deployment setting(s).&#x20;
{% endhint %}

#### **Suggested Actions**

* Conduct regular and sustained engagement with potentially impacted communities.
* Regularly test and evaluate systems in non-optimized conditions.
* Evaluate feedback from stakeholder engagement activities, in collaboration with human factors and socio-technical experts.
* Collaborate with socio-technical, human factors, and UI/UX experts to identify notable characteristics in context of use that can be translated into system testing scenarios.
* Measure AI systems prior to deployment in conditions similar to expected scenarios.
* Measure and document performance criteria such as validity (false positive rate, false negative rate, etc.) and efficiency (training times, prediction latency, etc.) related to ground truth within the deployment context of use.
* Measure assurance criteria such as AI actor competency and experience.
* Document differences between measurement setting and the deployment environment(s).

***

### :hand\_splayed:Representativeness

{% hint style="info" %}
#### **Definition**

Evaluations involving human subjects meet applicable requirements (including human subject protection) and are representative of the relevant population.
{% endhint %}

#### **Suggested Actions**

* Follow human subjects research requirements, as established by organizational and disciplinary requirements, including informed consent and compensation, during dataset collection activities.
* Analyze differences between intended and actual population of users or data subjects, including likelihood for errors, incidents or negative impacts.
* Utilize disaggregated evaluation methods (e.g. by race, age, gender, ethnicity, ability, region) to improve AI system performance when deployed in real world settings.
* Establish thresholds and alert procedures for dataset representativeness within the context of use.
* Construct datasets in close collaboration with experts with knowledge of the context of use.
* Evaluate data representativeness through
  * investigating known failure modes
  * assessing data quality and diverse sourcing
  * applying public benchmarks
  * traditional bias testing
  * chaos engineering
  * stakeholder feedback
* Maintain a demographically diverse and multidisciplinary and collaborative internal team.

***

### :woman\_technologist:Deployment

{% hint style="info" %}
#### **Definition**

The AI system to be deployed is demonstrated to be valid and reliable. Limitations of the generalizability beyond the conditions under which the technology was developed are documented.
{% endhint %}

#### **Suggested Actions**

* Define the operating conditions and socio-technical context under which the AI system will be validated.
* Define and document processes to establish the system’s operational conditions and limits.
* Establish or identify, and document approaches to measure forms of validity, including:
  * construct validity (the test is measuring the concept it claims to measure)
  * internal validity (relationship being tested is not influenced by other factors or variables)
  * external validity (results are generalizable beyond the training condition)
  * the use of experimental design principles and statistical analyses and modeling
* Assess and document system variance. Standard approaches include confidence intervals, standard deviation, standard error, bootstrapping, or cross-validation.
* Establish or identify, and document robustness measures.
* Establish or identify, and document reliability measures.
* Establish practices to specify and document the assumptions underlying measurement models to ensure proxies accurately reflect the concept being measured.
* Utilize standard software testing approaches (e.g. unit, integration, functional and chaos testing, computer-generated test cases, etc).
* Utilize standard statistical methods to test bias, inferential associations, correlation, and covariance in adopted measurement models.
* Utilize standard statistical methods to test variance and reliability of system outcomes.
* Monitor operating conditions for system performance outside of defined limits.
* Identify approaches for exploring AI system limitations, including testing scenarios that differ from the operational environment. Consult experts with knowledge of specific context of use.
* Define post-alert actions. Possible actions may include:
  * alerting other relevant AI actors before action
  * requesting subsequent human review of action
  * alerting downstream users and stakeholder that the system is operating outside it’s defined validity limits
  * tracking and mitigating possible error propagation
  * action logging
* Log input data and relevant system configuration information whenever there is an attempt to use the system beyond its well-defined range of system validity.
* Modify the system over time to extend its range of system validity to new operating conditions.

***

### :safety\_pin:Safety

{% hint style="info" %}
#### **Definition**

AI system is evaluated regularly for safety risks. The AI system to be deployed is demonstrated to be safe, its residual negative risk does not exceed the risk tolerance. Safety metrics implicate system reliability and robustness, real-time monitoring, and response times for AI system failures.
{% endhint %}

#### **Suggested Actions**

* Thoroughly measure system performance in development and deployment contexts, and under stress conditions.
* Align measurement to the goal of continuous improvement. Seek to increase the range of conditions under which the system is able to fail safely through system modifications in response to in-production testing and events.
* Document, practice and measure incident response plans for AI system incidents, including measuring response and down times.

***

### :closed\_lock\_with\_key:Security and Resilience

{% hint style="info" %}
#### **Definition**

AI system security and resilience are evaluated and documented.
{% endhint %}

#### **Suggested Actions**

* Establish and track AI system security tests and metrics (e.g., red-teaming activities, frequency and rate of anomalous events, system down-time, incident response times, time-to-bypass, etc.).

***

### :thinking:Explainability

{% hint style="info" %}
#### **Definition**

The AI model is explained, validated, and documented, and AI system output is interpreted within its context.
{% endhint %}

#### **Suggested Actions**

* Verify systems are developed to produce explainable models, post-hoc explanations and audit logs.
* When possible or available, utilize approaches that are inherently explainable, such as traditional and penalized generalized linear models , decision trees, nearest-neighbor and prototype-based approaches, rule-based models, generalized additive models , explainable boosting machines and neural additive models.
* Test explanation methods and resulting explanations prior to deployment to gain feedback from relevant end users, and potentially impacted individuals or groups about whether explanations are accurate, clear, and understandable.
* Document AI model details including model type (e.g., convolutional neural network, reinforcement learning, decision tree, random forest, etc.) data features, training algorithms, proposed uses, decision thresholds, training data, evaluation data, and ethical considerations.
* Establish, document, and report performance and error metrics across demographic groups and other segments relevant to the deployment context.
* Test the quality of system explanations with end-users and other groups.

***

### :file\_folder:Documentation

{% hint style="info" %}
#### **Definition**

Test sets, metrics, and details about the tools used during test, evaluation, validation, and verification are documented.
{% endhint %}

#### **Suggested Actions**

* Leverage existing industry best practices for transparency and documentation of all possible aspects of measurements. Examples include: data sheet for data sets, model cards, etc.
* Regularly assess the effectiveness of tools used to document measurement approaches, test sets, metrics, processes and materials used.

