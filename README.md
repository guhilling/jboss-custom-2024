* Logging (Ch.7, p. 305)

  See https://access.redhat.com/documentation/en-us/red_hat_jboss_enterprise_application_platform/7.4/html/configuration_guide/logging_with_jboss_eap#logging_profiles

  * Add new profile with provided logging-profile.cli
  * Extract logtest.war to directory logtraining.war
  * Add the manifest entry ```Logging-Profile: training```
  * Deploy with ```--unmanaged```

* Security (Ch.9, p. 387)

  See https://access.redhat.com/documentation/en-us/red_hat_jboss_enterprise_application_platform/7.4/html/how_to_configure_identity_management/elytron_secure_apps#elytron_apps_DBAuth

  * Create DB resources as described.
  * In 3. (p. 389), use the provided ```create-db-security.cli``` instead.
