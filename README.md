# AWS to decode aws backup error messages:- open aws cli
#aws sts decode-authorization-message --encoded-message (paste error message) --query DecodedMessage --output text
#--output text | jq '.'
