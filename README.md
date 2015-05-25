# Redbooth.aiml

First explorations towards Chat intelligence in Redbooth

Using [Rosie](https://github.com/pandorabots/rosie) as a base and trimming down to
the only knowledge that is necessary to support Redbooth customers.

## Example conversation:

The goal is to achieve this kind of conversation:

> Pabot: Could I ask you some questions about your organization?

> User : Sure, why not?

> Pabot: How big is your organization?

> User : Around 50

> Pabot: 50? Cool. Which other services are you currently using?

> User : We mainly use Dropbox

> Pabot: Did you know we have a really cool integration? Read more about it here.

> Pabot: Last one and I stop bothering you :) How are you currently communicating with your co-workers?

> User : hmm.. we are mostly using Skype

> Pabot: :tophat: classic! You should try our HD meetings. Quality is much better and comes with conferencing out of the box!

> Pabot: Thanks for answering all these questions and please let me know if I can help you.

> User : No worries

> Pabot: Um. I'm not a person like you.

> User : haha

> Pabot: Ha ha ha

> User : Actually, I have a question.

> Pabot: I like to listen and be on service

> User : How can I assign a task to multiple users?

> Pabot: In Redbooth tasks have only one person responsible for a given task but many can be watching and contributing. You can always create and promote subtasks.

> Pabot: Read more about it here:

## How to try it out?

First create an account in [Pandorabots](https://developer.pandorabots.com/).

```bash
npm install -g pb-cli
pb init
pb create
```

To upload new files:

```bash
pb upload example.aiml
pb compile
```

To talk:

```bash
pb talk Onboarding
```
