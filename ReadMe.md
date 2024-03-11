For testing the supplier portal api's in order to get them into Azure APIM

The agressoswaggerdefsOriginal.json file is the full suite of api's from Business World standard and currently fails when trying to import into the Azure APIM

The agresso_swagger_supp_portal.json is the file being built to specifically import the apis used by the Supplier Portal.
So far imported all Objects apis into Azure APIM

The raw content for the apim is:

https://raw.githubusercontent.com/Adamski443/jsontest/main/agresso_swagger_supp_portal.json

Last one added to APIM:
/v1/query/funder-schemes - failed
/v1/query/fixed-assets - success
/v1/query/flexi-fields-group-definition-details - failed
/v1/query/flexi-fields-group-definition -

