---
game: 
environment: 
tags: 
author:
---
## Nancy's Letters
<!-- QueryToSerialize: Table WITHOUT ID file.link as document, recepient from "content/X/Library" where contains(tags, "case-file") -->
<!-- SerializedQuery: Table WITHOUT ID file.link as document, recepient from "content/X/Library" where contains(tags, "case-file") -->

| document | recepient |
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
