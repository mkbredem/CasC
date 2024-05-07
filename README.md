# CasC
Configuration As Code

# Unencrypted Vars
web_server: some_webserver.com
web_user: <user or service account on webserver>


# Vault encrypted to protect secrets
# Example group_vars/all/controller_creds.yml
vault_controller_username: admin
vault_controller_password: SuperSecretPassword
vault_controller_hostname: some_controller.com
vault_controller_validate_certs: false

