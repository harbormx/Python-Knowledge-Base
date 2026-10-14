## This index and structure are subject to change as the project evolves.

python-knowledge-base/
│
├── README.md
├── REPRESENTATIVE-CONTENT.md
├── GLOSSARY.md
├── CONTRIBUTING.md
├── LICENSE
├── CHANGELOG.md
├── pyproject.toml
│
├── .github/
│ ├── ISSUE_TEMPLATE/
│ ├── PULL_REQUEST_TEMPLATE.md
│ └── workflows/
│
├── 00-START-HERE/
│ ├── repository-guide.md
│ ├── learning-paths.md
│ ├── how-to-use-this-guide.md
│ └── python-roadmap.md
│
├── 01-PYTHON-FUNDAMENTALS/
│ ├── syntax-and-semantics.md
│ ├── variables-and-naming.md
│ ├── data-types/
│ ├── operators.md
│ ├── conditionals.md
│ ├── loops.md
│ ├── functions/
│ ├── scope-and-namespace.md
│ ├── mutability-and-immutability.md
│ ├── truthiness.md
│ ├── comprehensions.md
│ ├── unpacking.md
│ └── idiomatic-python.md
│
├── 02-DATA-STRUCTURES/
│ ├── strings/
│ ├── lists/
│ ├── tuples/
│ ├── dictionaries/
│ ├── sets/
│ ├── bytes-and-bytearray.md
│ ├── collections-module/
│ ├── iterables-and-iterators.md
│ ├── generators.md
│ └── data-structure-comparisons.md
│
├── 03-FUNCTIONAL-PROGRAMMING/
│ ├── first-class-functions.md
│ ├── lambda.md
│ ├── closures.md
│ ├── decorators/
│ ├── higher-order-functions.md
│ ├── map-filter-zip.md
│ ├── itertools.md
│ └── functools.md
│
├── 04-OBJECT-ORIENTED-PROGRAMMING/
│ ├── classes-and-objects.md
│ ├── instance-and-class-attributes.md
│ ├── inheritance.md
│ ├── polymorphism.md
│ ├── encapsulation.md
│ ├── composition-vs-inheritance.md
│ ├── dataclasses.md
│ ├── properties.md
│ ├── descriptors.md
│ ├── protocols-and-abc.md
│ └── magic-methods.md
│
├── 05-ADVANCED-PYTHON/
│ ├── iterators-and-generators.md
│ ├── context-managers.md
│ ├── exceptions-and-chaining.md
│ ├── decorators-advanced.md
│ ├── closures-and-scopes.md
│ ├── metaclasses.md
│ ├── reflection-and-introspection.md
│ ├── dynamic-attributes.md
│ ├── descriptors.md
│ └── python-data-model.md
│
├── 06-TYPE-HINTS-AND-STATIC-TYPING/
│ ├── basic-type-hints.md
│ ├── collections-and-generics.md
│ ├── union-and-optional.md
│ ├── protocols.md
│ ├── typed-dictionaries.md
│ ├── callable-types.md
│ ├── generics.md
│ ├── overload.md
│ ├── type-narrowing.md
│ └── mypy-pyright/
│
├── 07-STANDARD-LIBRARY/
│ ├── pathlib.md
│ ├── os-and-sys.md
│ ├── shutil.md
│ ├── subprocess.md
│ ├── datetime.md
│ ├── re.md
│ ├── json.md
│ ├── csv.md
│ ├── logging.md
│ ├── argparse.md
│ ├── itertools.md
│ ├── functools.md
│ ├── collections.md
│ ├── enum.md
│ ├── dataclasses.md
│ ├── typing.md
│ ├── concurrent-futures.md
│ └── importlib.md
│
├── 08-MODULES-PACKAGES-AND-IMPORTS/
│ ├── modules.md
│ ├── packages.md
│ ├── init-py.md
│ ├── absolute-vs-relative-imports.md
│ ├── import-system.md
│ ├── sys-path.md
│ ├── circular-imports.md
│ ├── package-architecture.md
│ └── entry-points.md
│
├── 09-ENVIRONMENTS-DEPENDENCIES-PACKAGING/
│ ├── python-installation.md
│ ├── interpreters-and-versions.md
│ ├── venv.md
│ ├── pip.md
│ ├── dependency-locking.md
│ ├── pyproject-toml.md
│ ├── build-backends.md
│ ├── package-distribution.md
│ ├── wheels-and-sdists.md
│ ├── editable-installs.md
│ └── uv-poetry-pip-tools/
│
├── 10-DEBUGGING-AND-ERROR-HANDLING/
│ ├── traceback-reading.md
│ ├── pdb.md
│ ├── breakpoint.md
│ ├── vscode-debugging.md
│ ├── common-errors/
│ ├── logging-strategies.md
│ ├── debugging-workflows.md
│ ├── root-cause-analysis.md
│ └── memory-debugging.md
│
├── 11-TESTING-AND-QUALITY/
│ ├── testing-fundamentals.md
│ ├── pytest/
│ ├── unittest.md
│ ├── fixtures.md
│ ├── parametrization.md
│ ├── mocking.md
│ ├── test-doubles.md
│ ├── coverage.md
│ ├── property-based-testing.md
│ ├── mutation-testing.md
│ ├── linting-and-formatting/
│ ├── ruff.md
│ ├── black.md
│ ├── pylint.md
│ └── pre-commit.md
│
├── 12-CONCURRENCY-AND-PARALLELISM/
│ ├── threading.md
│ ├── multiprocessing.md
│ ├── asyncio/
│ ├── async-await.md
│ ├── event-loop.md
│ ├── concurrent-futures.md
│ ├── gil.md
│ └── concurrency-vs-parallelism.md
│
├── 13-DESIGN-AND-ARCHITECTURE/
│ ├── clean-code.md
│ ├── solid.md
│ ├── dry-kiss-yagni.md
│ ├── design-patterns/
│ ├── dependency-injection.md
│ ├── separation-of-concerns.md
│ ├── error-handling-strategies.md
│ ├── refactoring.md
│ ├── technical-debt.md
│ └── project-structure.md
│
├── 14-PERFORMANCE-AND-MEMORY/
│ ├── time-complexity.md
│ ├── profiling/
│ ├── timeit.md
│ ├── cprofile.md
│ ├── memory-profiling.md
│ ├── generators-and-memory.md
│ ├── caching.md
│ ├── garbage-collection.md
│ └── optimization-strategies.md
│
├── 15-FILES-DATA-AND-INTEGRATIONS/
│ ├── file-io.md
│ ├── encodings.md
│ ├── csv-json-xml-yaml.md
│ ├── regex.md
│ ├── http-requests/
│ ├── rest-apis/
│ ├── database-access/
│ ├── sockets-and-networking.md
│ ├── environment-variables.md
│ └── subprocess-automation.md
│
├── 16-AUTOMATION-AND-APPLICATIONS/
│ ├── filesystem-automation/
│ ├── cli-applications/
│ ├── web-scraping/
│ ├── api-automation/
│ ├── report-generation/
│ ├── workflow-automation/
│ └── task-scheduling.md
│
├── 17-PYTHON-AND-AI/
│ ├── llm-apis/
│ ├── model-sdks.md
│ ├── structured-outputs.md
│ ├── tool-calling.md
│ ├── embeddings-and-rag.md
│ ├── agent-frameworks.md
│ ├── evaluation-and-testing.md
│ └── ai-application-security.md
│
├── 18-DEVOPS-AND-CICD/
│ ├── git-workflows.md
│ ├── github-actions/
│ ├── jenkins/
│ ├── ci-pipelines.md
│ ├── docker-and-python.md
│ ├── environment-configuration.md
│ ├── artifact-management.md
│ └── release-automation.md
│
├── 19-PYTHON-IN-AUTOMOTIVE/
│ ├── python-for-ecu-testing.md
│ ├── can-lin-ethernet-integrations.md
│ ├── test-automation.md
│ ├── hil-sil-mil.md
│ ├── log-analysis.md
│ ├── test-reporting.md
│ └── bdd-and-gherkin/
│
├── 20-RECIPES-CHEATSHEETS-TROUBLESHOOTING/
│ ├── python-idioms.md
│ ├── built-in-functions.md
│ ├── common-code-patterns.md
│ ├── git-and-python.md
│ ├── regex-recipes.md
│ ├── common-exceptions.md
│ ├── environment-problems.md
│ └── debugging-cookbook/
│
├── 21-EXERCISES-AND-PROJECTS/
│ ├── beginner/
│ ├── intermediate/
│ ├── advanced/
│ ├── testing-projects/
│ ├── automation-projects/
│ └── capstone-projects/
│
├── 22-REFERENCE/
│ ├── built-in-functions.md
│ ├── built-in-types.md
│ ├── operators.md
│ ├── exceptions.md
│ ├── dunder-methods.md
│ ├── environment-variables.md
│ ├── python-version-matrix.md
│ └── official-resources.md
│
└── 99-TEMPLATES/
├── concept.md
├── module.md
├── library.md
├── tool.md
├── tutorial.md
├── troubleshooting.md
├── comparison.md
└── code-recipe.md
