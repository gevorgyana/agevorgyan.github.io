---
layout: default
permalink: clang-basic-directory
---

This post is about Clang's Basic/ directory classes. 

It is an overview of the selected topic from this site.

The first section is about SourceManager, SourceLocation, SourceManagerInternals.

The second section is about FileManager, FileEntry. 

The goal of studing the previous two sections is to get used to creating buffers by yourself in clang. 
It would be good to learn to create an in-memory buffer and initialize it with a string literal for testing purposes.

The third section is about using Diagnostics class. It covers the following classes: 

Diagnostic.h
Diagnostic.td
DiagnosticAST.h
DiagnosticASTKinds.td
DiagnosticAnalysis.h
DiagnosticAnalysisKinds.td
DiagnosticCategories.h
DiagnosticCategories.td
DiagnosticComment.h
DiagnosticCommentKinds.td
DiagnosticCommonKinds.td
DiagnosticCrossTU.h
DiagnosticCrossTUKinds.td
DiagnosticDocs.td
DiagnosticDriver.h
DiagnosticDriverKinds.td
DiagnosticError.h
DiagnosticFrontend.h
DiagnosticFrontendKinds.td
DiagnosticGroups.td
DiagnosticIDs.h
DiagnosticLex.h
DiagnosticLexKinds.td
DiagnosticOptions.def
DiagnosticOptions.h
DiagnosticParse.h
DiagnosticParseKinds.td
DiagnosticRefactoring.h
DiagnosticRefactoringKinds.td
DiagnosticSema.h
DiagnosticSemaKinds.td
DiagnosticSerialization.h
DiagnosticSerializationKinds.td
DirectoryEntry.h
