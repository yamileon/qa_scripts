teraform files to build simple py server on azure vm



to get ip of vm created by script

az network public-ip show --name tfvmex-publicip -g tfvmex-resources | jq -r '.ipAddress'
