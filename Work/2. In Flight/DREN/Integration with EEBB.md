- DREN Events are encrypted.
	- See [[EEBB Configurations]] for details on how to configure encryption/decryption of events.

##### Sample Events

###### Encrypted Event
```
[
    {
        "id": "0cb9d8db-6901-41b3-8d53-c3b59f82c818",
        "source": "DREN",
        "data":
        {
            "headers":
            {
                "eventId": "0cb9d8db-6901-41b3-8d53-c3b59f82c818",
                "producerName": "DREN_DISPATCHER",
                "source": "DREN",
                "channel": "DREN"
            },
            "dataGovernance":
            {
                "catalogId": "DREN_DISPATCHER",
                "containsPCI": false,
                "containsPII": true
            },
            "body":
            {
                "encryptedData":
                {
                    "message": "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",
                    "initializationVector": "7NzONpzuCqhalHAP",
                    "fullKeyUri": "https://ei-resorttech-uw-kv-da.vault.azure.net/secrets/EncryptionKey/62fe9c3f0c344673abc68bf202e65d0e"
                }
            }
        },
        "type": "DREN",
        "time": "2024-02-09T10:41:14.217654006Z",
        "specversion": "1.0",
        "datacontenttype": "text/plain",
        "subject": "Deposit Receipt Notification Data",
        "bodyversion": "1.0",
        "traceparent": "00-f30f175192b79fa096acd6dd97eda0ce-e6157fa98b399c21-01",
        "dataversion": "1.0"
    }
]
```

###### After Decryption

> **_Note**: this is not the correct format but gives you a good idea of the decryption process. RTC expects `rtcEventBody` as a JSON object under the EEBB event body (its passed as a string here)_

```
{
    "id": "3dad5cd3-9e17-4bcd-8e0a-4027a2e4bf01",
    "source": "DREN",
    "data":
    {
        "headers":
        {
            "eventId": "3dad5cd3-9e17-4bcd-8e0a-4027a2e4bf01",
            "producerName": "DREN_DISPATCHER",
            "source": "DREN",
            "channel": "DREN"
        },
        "dataGovernance":
        {
            "catalogId": "DREN_DISPATCHER",
            "containsPCI": false,
            "containsPII": true
        },
        "body": "{\"rtcEventBody\":{\"id\":\"100\",\"type\":\"DREN\",\"source\":\"DREN\",\"metadata\":{\"source\":\"LOYALTY\",\"receiver\":\"RTC\",\"marketing\":false},\"rtcEvents\":[{\"emailAddress\":\"azpatel@mgmresorts.com\",\"notificationType\":\"EMAIL\",\"eventId\":100,\"subject\":\"Deposit Receipt Notification Data\",\"body\":\"{\\\"first_name\\\":\\\"Jimmy\\\",\\\"last_name\\\":\\\"Marsh\\\",\\\"primary_email_id\\\":\\\"azpatel@mgmresorts.com\\\",\\\"secondary_email_id\\\":\\\"azpatel@mgmresorts.com\\\",\\\"opt_in\\\":\\\"TRUE\\\",\\\"customer_address\\\":\\\"445 Povfab Junction\\\",\\\"resort_name\\\":\\\"MGM Resort\\\",\\\"resort_id\\\":\\\"7\\\",\\\"check_in_date\\\":\\\"2023-09-15T14:00:00.00Z\\\",\\\"check_out_date\\\":\\\"2023-09-16T12:00:00.00Z\\\",\\\"confirmation_number\\\":\\\"16549\\\",\\\"arrival_date\\\":\\\"2023-09-15T07:46:14.00Z\\\",\\\"departure_date\\\":\\\"2023-09-16T19:46:14.00Z\\\",\\\"room_number\\\":\\\"49\\\",\\\"room_type_preference\\\":\\\"delux\\\",\\\"receipt_no\\\":\\\"95557004\\\",\\\"date_deposit_charged\\\":\\\"2023-09-12T19:46:14.00Z\\\",\\\"cc_type\\\":\\\"visa\\\",\\\"cc_number\\\":\\\"9.17E+15\\\",\\\"cc_expiry_date\\\":\\\"8/16/1926\\\",\\\"group_id\\\":\\\"904\\\",\\\"deposit_amount\\\":\\\"76840\\\",\\\"deposit_receipt_link\\\":\\\"http://sample-uploaded-csv-file-url\\\",\\\"current_date\\\":\\\"2023-09-12T19:46:14.00Z\\\"}\",\"identifiers\":[{\"identifierType\":\"MGM_ID\",\"value\":\"16549\"}],\"priority\":1}]}}"
    },
    "type": "DREN",
    "time": "2024-02-09T10:41:14.217654006Z",
    "specversion": "1.0",
    "datacontenttype": "text/plain",
    "subject": "Deposit Receipt Notification Data",
    "bodyversion": "1.0",
    "dataversion": "1.0"
}
```

###### Sample Code (for Decrypting the message)

_Notes: See more details [here](https://mgmdigitalventures.atlassian.net/wiki/spaces/DVE/pages/2290811957/Using+the+Subscriber+Library+-+Java)
- Managed Identities are not supported if you are running your application on your machine (localhost) and your logged in user will be used regardless of the values set in the `ConfigurationSettings`
- When running in Azure, if you specify `KeyVault/StorageAccountUserAssignedManagedIdentityClientId` then that user managed identity will be used.
- When running in Azure and you **don’t** specify `KeyVault/StorageAccountUserAssignedManagedIdentityClientId` then if a System assigned managed identity will be attempted to be used.

```java
private String decrypt(String encryptedString) throws MessageDecryptionException {

        ConfigurationSettings cfg = new ConfigurationSettings();
        cfg.setMessagesEncrypted(true);
        //cfg.setKeyVaultUserAssignedManagedIdentityClientId("712a18b5-8a80-4496-a109-e463616797cf");

        Subscriber subscriber = new Subscriber(cfg, new LoggerNull());
        try {
            return subscriber.TransformToString(encryptedString);
        } catch (InvalidAlgorithmParameterException e) {
            throw new MessageDecryptionException("InvalidAlgorithmParameterException", e);
        } catch (NoSuchPaddingException e) {
            throw new MessageDecryptionException("NoSuchPaddingException", e);
        } catch (IllegalBlockSizeException e) {
            throw new MessageDecryptionException("IllegalBlockSizeException", e);
        } catch (URISyntaxException e) {
            throw new MessageDecryptionException("URISyntaxException", e);
        } catch (NoSuchAlgorithmException e) {
            throw new MessageDecryptionException("NoSuchAlgorithmException", e);
        } catch (BadPaddingException e) {
            throw new MessageDecryptionException("BadPaddingException", e);
        } catch (InvalidKeyException e) {
            throw new MessageDecryptionException("InvalidKeyException", e);
        } catch (InvocationTargetException e) {
            throw new MessageDecryptionException("InvocationTargetException", e);
        } catch (InstantiationException e) {
            throw new MessageDecryptionException("InstantiationException", e);
        } catch (IllegalAccessException e) {
            throw new MessageDecryptionException("IllegalAccessException", e);
        }
    }
```