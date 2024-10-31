
# Leanalyze

Leanalyze is a repository designed to help users learn and analyze Lean programs. It provides practical examples, tutorials, and explanations to enhance your understanding of the Lean theorem prover.

## Table of Contents
- [About](#about)
- [Installation](#installation)
- [Getting Started](#getting-started)
- [Examples](#examples)
- [Use Cases](#use-cases)
- [Contributing](#contributing)
- [License](#license)

## About
Leanalyze is a collection of Lean files that showcase various features of the Lean programming language and proof assistant. It aims to make learning Lean easier through real-world examples and structured tutorials, helping users to:
- Understand Lean syntax and semantics.
- Explore theorem proving with Lean.
- Learn mathematical proofs and logic with step-by-step examples.

## Installation

To use Leanalyze, you need to have Lean installed on your system. Follow the steps below to get started:

1. Install Lean using the official documentation: [Lean Installation Guide](https://leanprover.github.io/).
2. Clone this repository:
    ```bash
    git clone https://github.com/vrtheking/leanalyze.git
    cd leanalyze
    ```
3. Ensure you have Lean and mathlib set up properly.

## Getting Started

Once Lean is installed, navigate to any of the Lean files in the `examples/` directory to begin. You can open these files using a Lean IDE plugin such as [VS Code](https://code.visualstudio.com/) with the Lean extension.

To check the validity of the Lean files, open them and use Lean's check functionality within the IDE.

### Example Commands
You can use Lean's built-in commands to interact with files:
- Type-check a file:
    ```bash
    lean --check example.lean
    ```
- Run a Lean script:
    ```bash
    lean example.lean
    ```

## Examples

The `examples/` directory contains multiple Lean files that cover a range of topics:

- **Basic Arithmetic**: Simple proofs involving addition, multiplication, etc.  
  Example: [basic_arithmetic.lean](examples/basic_arithmetic.lean)

- **Propositional Logic**: Learn how to work with logical statements and proofs.  
  Example: [propositional_logic.lean](examples/propositional_logic.lean)

- **Set Theory**: Explore sets and operations on sets.  
  Example: [set_theory.lean](examples/set_theory.lean)

- **Inductive Types**: Dive into creating and using inductive types in Lean.  
  Example: [inductive_types.lean](examples/inductive_types.lean)

- **Proof by Induction**: Understand the proof by induction technique.  
  Example: [proof_by_induction.lean](examples/proof_by_induction.lean)

## Use Cases

Leanalyze can be used in a variety of contexts:
- **Mathematics Education**: Learn how to use Lean to prove mathematical theorems.
- **Logic and Philosophy**: Explore logical reasoning and formal proofs.
- **Computer Science**: Understand how Lean applies to functional programming and type theory.
- **Automated Theorem Proving**: Develop skills in formal verification and proof automation.

Each Lean file comes with detailed comments explaining the key concepts and proofs step by step.

## Contributing

We welcome contributions! If you'd like to contribute to Leanalyze, please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request with a detailed description of the changes.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
