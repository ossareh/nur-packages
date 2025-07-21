This project uses the default template at: https://github.com/nix-community/nur-packages-template

I want to migrate it to a snowfall lib format: https://snowfall.org/guides/lib/quickstart/. I put my snowflake stuff in nix-config/

while keeping compatible with all that the default template does. Including the CI portion of this.

Ultimately the work seems to mostly be a case of copying pkgs/<pkg name>/default.nix into the corresponding nix-config/packages directories

For now lib, modules, and overlays can be ignored; I have removed these directories.
