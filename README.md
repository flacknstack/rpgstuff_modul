# RPG Extension for MyBB ACP

This module extends the MyBB Admin Control Panel (ACP) with the "RPG Extension" tab. It offers the same hooks as other modules and allows for future plugin management directly through the ACP. The module also includes two additional functions:

- Update Stylesheet: If stylesheets are lost due to a MyBB update, the stylesheets of associated plugins can be restored with a single click.

- Update Plugins: Allows you to configure update scripts via hooks, enabling convenient plugin updates with a single click.

# Set User Group Permissions
To grant all admin accounts access to the module in the ACP, the permissions must be adjusted under the Users & Groups » Administrator Permissions » User Group Permissions tab. The permissions for the module are located in the 'RPG Extensions' tab. All available options there must be set to "Yes".
