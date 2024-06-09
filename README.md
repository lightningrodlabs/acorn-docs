# What is Acorn?

{% hint style="danger" %}
This Acorn knowledge base is in its early stages of development and will be progressively adapted and updated.
{% endhint %}

Acorn is an open-source, peer-to-peer project management application. It is designed and built as a scrum-alternative, [Agile Development Pattern](https://en.wikipedia.org/wiki/Agile\_software\_development) for distributed software development teams.&#x20;

Acorn functions through defining [Intended Outcomes](about-acorn/the-ontology-of-acorn.md#outcomes) for a project in a [Dependency Tree](about-acorn/the-ontology-of-acorn.md#dependency-tree) structure.

Acorn is built as a [Holochain](https://holochain.org) application, meaning it runs on decentralized peer-to-peer computing and can be used without server infrastructure or a hosting service. The users of a particular Acorn instance are its hosting power.

## FAQ

### What license is Acorn under? Why?

Acorn is under the [Cryptographic Autonomy License v1.0](https://github.com/holochain/cryptographic-autonomy-license) (CAL), [approved by the Open Source Initiative (OSI)](https://opensource.org/licenses/CAL-1.0).

CAL was created for the Holochain project to protect both source code and user data from restriction. It frees an end user from having their data held from them by a party that develops or hosts software licensed under CAL.

### Who developed it?

Acorn was envisioned and prototyped (using a third party platform) by the [Holochain](https://holochain.org) core development team in 2018 to organize their own planning and execution process.

In August 2019 [Sprillow](https://sprillow.com) undertook a design process and began building Acorn on Holochain and continues to today. In June 2022 the first major release of Acorn (Alpha) was published and it's currently in an Alpha testing phase.

[Lightningrod Labs](https://lightningrodlabs.org) is the container for the continuous development of Acorn alongside some other projects powered by Holochain.

Please consult our [AUTHORS.md file](https://github.com/lightningrodlabs/acorn/blob/main/AUTHORS.md) for a list of contributors and their organizations.

### What are future plans for Acorn?

Acorn is being developed and improved on a regular basis, and is currently is in **Alpha** testing phase.

## Contributing

We welcome contributions from anyone to the Acorn project. Here are some ways that you can contribute.

### Log an issue

If you download Acorn, and use the software, you might occasionally run into some problems. If and when you do, those issues can be brought up with the Acorn development team, by logging an issue here in the Github repository for the project. If you have a Github account, or create one, you can do that here: [https://github.com/lightningrodlabs/acorn/issues/new](https://github.com/lightningrodlabs/acorn/issues/new)

When filing an issue, please include a detailed description of the following:

* which operating system you were using
* a list of steps you took that led to the issue ("steps to reproduce")
* a screenshot (if not sensitive information)

### Start a discussion

We do not have a separate 'chat' forum for Acorn, apart from the Discussions space on the Github project. Please use it to bring up questions, or to explore potentials. [https://github.com/lightningrodlabs/acorn/discussions](https://github.com/lightningrodlabs/acorn/discussions) It can also be a good space to connect with other Acorn users, and hear about how they're using Acorn.

### Contribute directly to the software, as a developer

If you are interested to contribute to Acorn's development, welcome! Acorn is written in languages such as Rust and Typescript, and frameworks such as Holochain, and React. If you have proficiency in either Typescript and React for writing frontend code, or Rust for writing backend code, or both, then you may find it intuitive to contribute. Generally, new features come through a design -> development pipeline defined by the workflows of the [Sprillow](https://sprillow.com) team, but these workflows could be adapted to more 'open' workflows if the right opportunity presented itself. Otherwise, contributions may remain more-so in the space of bug fixes and other technical-first features, such as algorithms or scripts.

It should be noted that while the Rust code has unit tests, the frontend code does not. That is another area for potential improvement (front end testing).

In terms of getting the codebase up and running on your local development machine, check out [DEVELOPERS.md](https://github.com/lightningrodlabs/acorn/blob/main/DEVELOPERS.md).

In terms of getting more familiar with the codebase, you can get a rather in-depth introduction by watching these two videos:

* Acorn technical deep dive, Part 1: [https://www.youtube.com/watch?v=PXrN\_H0I0ng](https://www.youtube.com/watch?v=PXrN\_H0I0ng)
* Acorn technical deep dive, Part 2: [https://www.youtube.com/watch?v=0VA9QcmoXeI](https://www.youtube.com/watch?v=0VA9QcmoXeI)

While some of that code may be out of date, the general introduction should still apply, and be helpful.

In terms of getting more deeply involved, talking with other contributors, just start by reaching out to [connor@sprillow.com](mailto:connor@sprillow.com) to explore what makes sense!
