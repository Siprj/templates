# What is this repository about?

This is my repository where I store project templates for my use. This whole
thing is powered by [project-init (pi)](https://github.com/vmchale/project-init).

## How to

`pi` doesn't support downloading git sub directories as templates (yet), so it
needs be first downloaded with this command:

```bash
git clone https://github.com/Siprj/templates ~/.pi_templates/templates
```

And then you can use any template form this repository with:

```bash
pi init templates/${TEMPLATE} ${PROJECT_NAME}
```
