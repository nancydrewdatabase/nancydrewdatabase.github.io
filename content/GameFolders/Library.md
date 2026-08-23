---
game: 
aliases: 
tags:
  - library
---
## Nancy's Letters
<!-- QueryToSerialize: Table WITHOUT ID file.link as document, recipient from "content/X/Library" where contains(tags, "case-file") -->
<!-- SerializedQuery: Table WITHOUT ID file.link as document, recipient from "content/X/Library" where contains(tags, "case-file") -->

| document | recipient |
| -------- | --------- |

<!-- SerializedQuery END -->

## Books
<!-- QueryToSerialize: Table WITHOUT ID file.link as document, environment, author from "content/X/Library" where contains(tags, "book") -->
<!-- SerializedQuery: Table WITHOUT ID file.link as document, environment, author from "content/X/Library" where contains(tags, "book") -->

| document | environment | author |
| -------- | ----------- | ------ |
<!-- SerializedQuery END -->

## Misc
<!-- QueryToSerialize: Table WITHOUT ID file.link as document, environment, author from "content/X/Library" where !contains(tags, "book") and !contains(tags, "case-file") -->
<!-- SerializedQuery: Table WITHOUT ID file.link as document, environment, author from "content/X/Library" where !contains(tags, "book") and !contains(tags, "case-file") -->

| document | environment | author |
| -------- | ----------- | ------ |
<!-- SerializedQuery END -->
