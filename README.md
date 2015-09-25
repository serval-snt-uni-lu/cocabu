# CoCaBu
Source code will be available soon.

# Input

To build the **Snippet Index**, we used the data dump of Stack Overflow posts ([StackExchange](https://archive.org/details/stackexchange)) between July 2008 and March 2015 containing 1,363,002 Java and Android tagged questions.

For the **Code Index**, we considered GitHub projects that are forked at least once (to avoid toy and/or inactive projects) and in which major language is “Java” and then removed all non-Java files.


# Datasets
To read/inspect the following indices you may use [Luke](https://github.com/DmitryKey/luke/releases/download/luke-4.10.4-field-reconstruction/luke-with-deps.jar). Luke allows to access, browse and display documents within an existing Lucene index.
## Fields

The following table illustrates the primary fields used to construct an augmented query:

| Field                      | Value                                         |
| -------------------------- |---------------------------------------------- |
| typed_method_call          | Partially qualified method invocations        |
| methods                    | Method Declarations                           |
| used_classes               | Name of used classes                          |
| methods_called             | Non-qualified method invocations              |
| literals                   | String literals                               |
| extends                    | Direct superclass and implemented interfaces  |
| class_instance_creation    | Class instance creations                      |

##  Download Indices

[Snippet Index](https://docs.google.com/uc?export=download&id=0BziVDm-Qdq5tR3dUUUx1QklCUGM)

[Code Index](https://docs.google.com/uc?export=download&id=0BziVDm-Qdq5tUHVnbUsyblY0emM)