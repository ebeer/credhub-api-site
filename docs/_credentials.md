# Credentials

Credentials are the primary object in CredHub. Any passwords, secrets, configurations or other sensitive information that you store is saved to a named credential. You can retrieve, update and delete a credential using its name. 

All credentials, regardless of type, share a common namespace, e.g. a credential named `/diego-tls` exists once in CredHub. Credential names are not reservable, so two users updating a credential of the same name will result in updates to the same credential. If you prefer a separate namespace for your credentials, you can add a path prior to the credential name.

Credentials are typed based on the format of the stored value, value validation and generation procedure. Once a credential type has been set, it can not be updated to a new type. If you mistakenly set the type, you must delete the credential, then set it with the correct type. 
