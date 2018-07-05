---
name: Custom issue template
about: Describe this issue template's purpose here.

---

<html>
query {
    organization(login:"github") {
    members(first: 100) {
      edges {
        node {
          name
          avatarUrl
        }
      }
    }
  }
}
</html>
