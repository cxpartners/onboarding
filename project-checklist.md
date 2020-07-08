# project-checklist

A checklist that can help generate ideas for project tasks and generate architectural decision records.
> With current best practices

## project inception

* How will you store and version control code
> set up code repository in Github
* How will you manage and protect environment variables?
> set up .gitignore file and use AWS Secrets
* How will you document architectural decision records?
> add [architectural decision records](https://github.com/joelparkerhenderson/architecture_decision_record/blob/master/adr_template_by_michael_nygard.md) to your repo

* Is this part of a programme or a stand alone project?
* What's the use-case?
* Is this an experiment?
* If so, what are you testing? what data will you need to collect?
* What could go wrong?
> Conduct a premortem, identifying everything that can go wrong then create actions to mitigate risks idenitified.
* What security risks could there be?
> Check against [OWASP Top 10](https://owasp.org/www-project-top-ten/)

## working with the client

* What can the client support?
* Does the client have a tech team?
* Can the client's tech team support the project?
* How will the project be socialised?
* What controls have the client got inplace?
* How can we deploy our solutions?

* Can we use cloud services?
* Should we buy/build the service?
> Use [Wardley maps](https://medium.com/wardleymaps) to determine

* Can the client provide access to necessary systems?
* How will we handover work?
* Who will maintain the work?
* How will this work be sustained?
* Does the client have code guidelines?
* Does the client do code reviews?

## analytics, monitoring and error reporting

* What data do we need to collect?
* Will we be a/b testing and iterating on what we deploy?
* What monitoring can we set up?
* How do we report build errors/downtime?
* Does the client do receive notifications?
* How does billing work?

## content and styling

* What content will we need?
* Do we need a content management system?
* What assets will we need?
* Does the client have brand / style guidelines?
* What are the Non-Functional Requirements?

## deployment
* How will this service be deployed?
* Can we use an existing docker image? Or use a project bootstrap/template?
* How can we employ Continuous Integration / Deployment?
> [Buddy](https://app.buddy.works/cxpartners)
* Do we need to set up a domain name or domain name records?
> [Gandi](https://admin.gandi.net/domain/da8a04ba-99d6-11e7-96dd-00163e6dc886/table)

## documentation
* How will you enable other developers to use your work
> add README file, create Architectural Diagram
