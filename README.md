# wildfirebill-unraid/unraid-configs

Unraid server configurations and Docker templates for Community Applications.

## Structure
- `templates/` - Docker application templates (.xml)
- `plugins/` - Plugin wrappers (.xml)
- `ca_profile.xml` - Community Applications repository profile
- `icon.svg` - Repository icon

## Adding Templates
1. Add Docker template XML files to `templates/`
2. Add plugin wrapper XML files to `plugins/`
3. Update `ca_profile.xml` if needed
4. Push to GitHub
5. Submit/Update at https://ca.unraid.net/submit

## Template URL Format
Docker templates must have TemplateURL pointing to raw GitHub URL:
```
https://raw.githubusercontent.com/wildfirebill-unraid/unraid-configs/main/templates/your-app.xml
```