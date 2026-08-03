# wildfirebill-unraid/unraid-configs

Unraid server configurations and Docker templates for Community Applications.

## Structure
- `templates/` - Docker application templates (.xml)
- `ca_profile.xml` - Community Applications repository profile
- `icon.svg` - Repository icon

## Adding Templates
1. Add Docker template XML files to `templates/`
2. Update `ca_profile.xml` if needed
3. Push to GitHub
4. Submit/Update at https://ca.unraid.net/submit

## Template URL Format
Docker templates must have TemplateURL pointing to raw GitHub URL:
```
https://raw.githubusercontent.com/wildfirebill-unraid/unraid-configs/main/templates/your-app.xml
```

> **Note:** Custom plugins are maintained in the separate [`unraid-plugins`](https://github.com/wildfirebill-unraid/unraid-plugins) repository.