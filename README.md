<p align="center">
 <img src="https://raw.githubusercontent.com/omermorad/OpenVersify/master/logo.jpg" alt="Logo" />
</p>

<h1 align="center">OpenVersify</h1>

<p align="center">
<strong>Team-driven and code-first platform, masterfully crafts OpenAPI specs, aligning 
development with APIs, and is optimized to scale with expansive team codebases.</strong>
</p>

## 🚀 Features

- **Version Management**: Effortlessly manage and track versions of your OpenAPI specifications.
- **SDK Management**: Ensure your SDKs are always up-to-date and in sync with your API changes.
- **Schema Synchronization**: Keep your request and response schemas consistent across all your APIs.
- **Team Collaboration**: Built with teams in mind, OpenVersify promotes collaborative API development.
- **Documentation Integration**: Automatically generate and update API documentation based on your latest changes.

## 🛠 Installation

```bash
# Use the package manager of your choice
npm install openversify
# or
yarn add openversify
```

**OpenVersify: A Deep Dive into Structure, Tools, and Architecture**

At its core, OpenVersify is a robust platform designed to revolutionize the OpenAPI development experience for teams.
Let's delve into the intricacies of its structure and the tools that power this transformative solution.

**Node & TypeScript**: The foundation of OpenVersify is built upon the dynamic duo of Node and TypeScript. Node provides
the runtime environment, ensuring fast execution and scalability. TypeScript, with its static typing, brings in the
much-needed reliability and maintainability to the codebase. This combination ensures that OpenVersify is not only
performant but also developer-friendly, allowing for easier debugging and enhanced code quality.

**Lerna**: Version management is pivotal in OpenVersify, and Lerna stands at the forefront of this. Lerna, a tool that
optimizes the management of JavaScript projects with multiple packages, is employed to handle semantic versioning. But
OpenVersify takes it a notch higher by integrating Lerna with semantic commits. This synergy, combined with the git
flow, ensures that versioning is not just systematic but also meaningful. Every commit translates to a tangible change,
making the version history both coherent and traceable.

**Playwright for E2E Testing**: Ensuring that the end product works seamlessly is paramount. Playwright, a modern
end-to-end testing framework, is harnessed to achieve this. What sets OpenVersify's testing apart is its meticulous
division by API versioning. This granularity ensures that each API version is rigorously tested for its unique features
and functionalities. Furthermore, Playwright's projects feature is leveraged to organize and manage these tests
efficiently, ensuring that each version gets the dedicated testing attention it deserves.

**Built-in CI & Documentation Integration**: Continuous Integration (CI) is embedded into OpenVersify's DNA. This
built-in CI ensures that every change, every update, seamlessly integrates with the existing setup without hitches. But
OpenVersify goes beyond just code integration. It has a dedicated mechanism to integrate documentation. As the code
evolves, so do the docs, ensuring that users always have the most updated and relevant information at their fingertips.

**OpenAPI Specs (Formerly Swagger)**: OpenAPI, the bedrock upon which OpenVersify stands, is a specification for
building APIs. Formerly known as Swagger, OpenAPI provides a standard, language-agnostic interface to RESTful APIs.
OpenVersify harnesses this specification, ensuring that the APIs crafted are not just powerful but also adhere to global
standards. This adherence guarantees interoperability, making it easier for developers across the globe to understand,
use, and even extend the APIs crafted with OpenVersify.

In essence, OpenVersify is not just a tool; it's an ecosystem. An ecosystem where cutting-edge tools and best practices
converge to offer a holistic OpenAPI development experience. Whether it's crafting the API, managing versions, testing,
or documentation, OpenVersify has got it all covered, making it the go-to solution for teams aiming for OpenAPI
excellence.

