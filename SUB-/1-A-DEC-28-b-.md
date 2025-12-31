



---





- 16:07 Intro to nvm
  - ( Installing Node.js the Right Way with NVM )
  - ( Node Version Manager )

---



---


![Intro to nvm][Chapter-01-E-ref]


---

## **Topic 7: The Development Environment & Node.js**

This section transitions from TypeScript theory to the physical infrastructure required to run modern development tools. It establishes Node.js as the non-negotiable foundation for the entire ecosystem.

| Timestamp | Subtopic | Key Details |
| --- | --- | --- |
| **00:16:35** | Node.js Fundamentals | **Rationale:** JavaScript was born for browsers, but Node.js allows it to run on your computer/servers.<br>

<br>**Implementation:** It provides the environment for tools like `npm`, compilers, and test runners to function. |
| **00:16:56** | The V8 Engine | **Rationale:** To explain the speed and reliability of the runtime.<br>

<br>**Implementation:** Node.js is built on Google's V8 engine, making it foundational for React and React Native development. |
| **00:17:35** | Version Management | **Rationale:** Different projects often require different versions of Node (e.g., v18 vs v20).<br>

<br>**Implementation:** Using a manager like **NVM** (Node Version Manager) is the professional baseline for avoiding "version pain." |

---

## **Topic 8: Tooling Strategy (NVM & LTS)**

Before writing a single line of TypeScript, the instructor emphasizes a "safety first" installation strategy to prevent future environment errors.

| Timestamp | Subtopic | Key Details |
| --- | --- | --- |
| **00:17:54** | Professional Setup | The "correct" workflow: Install **NVM** first, then use it to install **Node.js**. This ensures Node is managed and switchable from day one. |
| **00:18:27** | LTS vs. Experimental | **Rationale:** Stability is prioritized over "newness" for production work.<br>

<br>**Implementation:** Always aim for the **LTS** (Long-Term Support) version for a stable, widely supported development experience. |

---



---

## **Terminology & Vocabulary Improvement**

| Word/Phrase | Context | For Beginners (Simpler) | For Intermediate (Technical) |
| --- | --- | --- | --- |
| **"Runtime"** | Environment | The "engine" that runs the code. | Execution environment for a program. |
| **"NVM"** | Versioning | A switcher for different Node versions. | Node Version Manager for environmental sandboxing. |
| **"LTS"** | Software Lifecycle | The "Safe" and stable version. | Long-Term Support for enterprise-grade stability. |
| **"V8 Engine"** | Performance | The brain that reads JavaScript. | Google’s high-performance open-source JS engine. |

---


## **Transcript Error Detection & Corrections**

This section highlights potential phonetic misinterpretations by the AI transcription service or minor verbal slips.

| Timestamp | Original Text (SRT) | Likely Intended Word/Action | Context |
| --- | --- | --- | --- |
| **00:19:40** | `mpxtsc` | `npx tsc` | The transcript combined the runner `npx` with the command `tsc` into a single nonsense word. |
| **00:18:58** | `your terminal.` | `the terminal.` | Stylistic; "The terminal" is more standard, though "Your" is acceptable in tutorial contexts. |
| **00:19:36** | `install-g` | `install -g` | The transcript lacks the necessary space between the command and the flag, which would cause a syntax error if copied literally. |

---

## **Code Snippets & Analogies**

**[00:17:10] - The "Ground You're Standing On" Metaphor**
The instructor describes Node.js not as an optional library, but as the "ground" of the development process.

* **Deconstruction:** If TypeScript is the car you are driving, Node.js is the **pavement**. You cannot drive the car without the road beneath it. Every tool you use (React, NPM, Compilers) sits on top of this Node.js "ground."

**[00:18:12] - The Three-Step Foundation**
The plan for a stable setup is explicitly defined:

1. **Install nvm** (The Manager)
2. **Check Available Versions** (The Inventory)
3. **Install LTS** (The Stable Choice)

```bash
# Conceptual NVM Workflow based on [00:17:54]
nvm install --lts    # Downloads stable version
nvm use --lts        # Sets active version to stable
node -v              # Checks version currently in use

```

---





---

* 18:47 Installing Node.js
---

---

## **Topic 9: Installing NVM and Node.js**

This section focuses on the practical execution of setting up the development environment. It guides the user through the transition from conceptualizing version management to the actual terminal commands required for a professional setup.

| Timestamp | Subtopic | Key Details |
| --- | --- | --- |
| **00:18:48** | NVM Installation | **Rationale:** Accessing the source of truth for the version manager.<br>

<br>

<br>**Implementation:** Locate NVM on GitHub and use the provided `curl` command to install it via the terminal. |
| **00:19:10** | Managing Node Versions | **Rationale:** Verifying that the environment is correctly configured and ready for software.<br>

<br>

<br>**Implementation:** Use `nvm` commands to list available versions and specifically install the **LTS** (Long-Term Support) version. |
| **00:19:26** | Node Package Manager (npm) | **Rationale:** Once Node is active, you gain access to the world’s largest software registry.<br>

<br>

<br>**Implementation:** Use `npm` as the primary tool to manage and install external libraries like TypeScript. |

---

## **Topic 10: Global TypeScript Configuration**

With the foundation laid, the instructor moves to the final step: making TypeScript accessible throughout the entire operating system to begin the development process.

| Timestamp | Subtopic | Key Details |
| --- | --- | --- |
| **00:19:33** | Global Installation | **Rationale:** Installing TypeScript globally allows you to run compiler commands from any folder/project.<br>

<br>

<br>**Implementation:** Execute `npm install -g typescript` to bind the language tools to your system path. |
| **00:19:40** | Verification & TSC | **Rationale:** Confirming a successful installation before proceeding to code.<br>

<br>

<br>**Implementation:** Use `npx tsc --version` to verify that the TypeScript Compiler is active and identify the specific version installed. |

---

## **Terminology & Vocabulary Improvement**

| Word/Phrase | Context | For Beginners (Simpler) | For Intermediate (Technical) |
| --- | --- | --- | --- |
| **"Curl Command"** | Installation | A way to download files using the terminal. | A command-line tool for transferring data with URLs. |
| **"Global Install"** | Scope | Installing a tool so it works everywhere on your computer. | Adding a package to the system's global binary path (`-g`). |
| **"npm"** | Package Management | A tool that downloads and manages code libraries. | Node Package Manager; the default registry for JS modules. |
| **"tsc"** | Compilation | The tool that turns TypeScript into JavaScript. | The TypeScript Compiler; responsible for type-checking and transpilation. |

---


## **Transcript Error Detection & Corrections**

This section highlights potential phonetic misinterpretations by the AI transcription service or minor verbal slips.

| Timestamp | Original Text (SRT) | Likely Intended Word/Action | Context |
| --- | --- | --- | --- |
| **00:19:40** | `mpxtsc` | `npx tsc` | The transcript combined the runner `npx` with the command `tsc` into a single nonsense word. |
| **00:18:58** | `your terminal.` | `the terminal.` | Stylistic; "The terminal" is more standard, though "Your" is acceptable in tutorial contexts. |
| **00:19:36** | `install-g` | `install -g` | The transcript lacks the necessary space between the command and the flag, which would cause a syntax error if copied literally. |

---

## **Code Snippets & Analogies**

**[00:18:55] - The "Direct Delivery" Analogy**
The instructor uses the `curl` command as a digital courier.

* **Deconstruction:** Think of the `curl` command as a specialized delivery service. Instead of visiting a website and clicking a "Download" button manually, you are giving the terminal a direct address (the URL) to go and fetch the installation package and bring it straight to your system.

**[00:19:33] - Global Foundation Setup**
The workflow for finalizing the environment is demonstrated through these terminal commands:

```bash
# Installation and Verification Workflow
# 1. Install TypeScript globally
npm install -g typescript

# 2. Verify the installation and check version
npx tsc --version

```




---

## Extra Notes

- Differences between the Windows and Linux/macOS versions of `nvm`.

| Feature           | Windows (nvm-windows)            | Linux/macOS/WSL (nvm)          |
|-------------------|----------------------------------|--------------------------------|
| **Set Default**    | `nvm use <version>`              | `nvm alias default lts/*`      |
| **Command Syntax** | `nvm install lts`                | `nvm install --lts`            |
| **Aliases**        | Not supported                    | Native support                 |





---


## **18:47 Installing Node.js**

---

### **Installation Instructions:**
- For installing Node.js, follow the instructions based on your operating system:

#### **For Linux/macOS:**
- Use the following command to install NVM (Node Version Manager):
  
  curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash



#### **For Windows:**

* Follow the instructions from [nvm-windows repository](https://github.com/coreybutler/nvm-windows)

### **Verify NVM Installation:**

* Run the following command to check the installed versions of Node.js:

  ```bash
  nvm list
  ```

---

### **Install Latest LTS (Long-Term Support) Version:**

* Run the command to install the latest LTS version of Node.js:

  ```bash
  nvm install --lts
  ```

#### **For Windows Users:**

* Use this command to install the latest LTS version on Windows:

  ```bash
  nvm install lts
  ```

---

### **Working with NVM on Windows:**

If you're using **Windows**, you'll see the following in your terminal:

```bash
C:\Users\saurav💠> nvm list
    24.12.0
```

You can switch between versions using:

```bash
C:\Users\saurav💠> nvm use lts
Now using node v24.12.0 (64-bit)
```

Verify the active version:

```bash
C:\Users\saurav💠> nvm list
  * 24.12.0 (Currently using 64-bit executable)
```

---

### **Installing TypeScript:**

To install TypeScript globally, use the following command:

```bash
C:\Users\saurav💠> npm install -g typescript
```

This will install TypeScript and show a confirmation like:

```
added 1 package in 3s
```

You will also be notified of a new minor version of npm:

```
npm notice New minor version of npm available! 11.6.2 -> 11.7.0
npm notice Changelog: https://github.com/npm/cli/releases/tag/v11.7.0
npm notice To update run: npm install -g npm@11.7.0
```

---

### **Verify TypeScript Installation:**

Check the installed version of TypeScript:

```bash
C:\Users\saurav💠> npx tsc --version
Version 5.9.3
```

---



---




---




[Chapter-01-A-ref]: ./1-A-DEC-28--SRC-/Screenshot%20(17941).png
[Chapter-01-B-ref]: ./1-A-DEC-28--SRC-/Screenshot%20(17944).png
[Chapter-01-C-ref]: ./1-A-DEC-28--SRC-/Screenshot%20(17945).png
[Chapter-01-D-ref]: ./1-A-DEC-28--SRC-/Screenshot%20(17947).png
[Chapter-01-E-ref]: ./1-A-DEC-28--SRC-/Screenshot%20(17950).png






---




---




---







---




---




---







---




---




---







---