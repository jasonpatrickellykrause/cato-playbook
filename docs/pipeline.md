

Our [continuous integration](https://www.martinfowler.com/articles/continuousIntegration.html) pipeline ensures that 
application teams can deliver products into production quickly and safely. Security and compliance concerns are 
addressed in the secure and release stages of the pipeline. The **Secure Release Pipeline** is a 
[Lighthouse product](https://github.com/department-of-veterans-affairs/lighthouse-tornado) that manages and enforces 
both the secure and release stages. Policy enforcement is achieved by 
[digitally signing](https://csrc.nist.gov/glossary/term/digital_signature) application images and validating them prior 
to deployment.

![Pipeline!](images/pipeline.png "CI/CD Pipeline")