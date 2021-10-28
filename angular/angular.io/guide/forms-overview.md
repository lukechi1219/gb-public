---
description: .
---

# forms-overview

.

#### Scalability <a href="scalability" id="scalability"></a>

If forms are a central part, scalability is very important. \
able to reuse form models across components is critical.

Reactive forms are more scalable than template-driven forms.&#x20;

They provide direct access to the underlying form API and use [synchronous data flow](https://angular.io/guide/forms-overview#data-flow-in-reactive-forms) between the view and the data model, which makes creating large-scale forms easier. \
\
Reactive forms require less setup for testing, and testing does not require a deep understanding of change detection to properly test form updates and validation.

Template-driven forms focus on simple scenarios and are not as reusable. \
They abstract away the underlying form API and use [asynchronous data flow](https://angular.io/guide/forms-overview#data-flow-in-template-driven-forms) between the view and the data model. \
\
The abstraction of template-driven forms also affects testing. Tests are deeply reliant on manual change detection execution to run properly and require more setup.

.
