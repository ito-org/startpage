# Startpage

This is a static bookmark page for the ito project based on homer.  [homer](https://github.com/bastienwirtz/homer), a dead simple static **HOM**epage for your serv**ER** to keep your services on hand, from a simple yaml configuration file.

![Yaml Check](https://github.com/ito-org/startpage/workflows/Yaml%20Check/badge.svg)

## Contribution

You can edit the Links on the page by editing the ``config.yml`` file. 

Examples:

```yaml
# Create a new entry
- name: "Title for the Entry"
  subtitle: "Link to the GitHub organization"
  # you can use icon ore logo like this:
  #icon: "fab fa-question"
  #logo: "/assets/to/logo.png" 
  tag: "code"
  url: "https://linktotheservice.com"
  target: '_blank' # optional html a tag target attribute
```
