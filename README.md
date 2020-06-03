# terraform-variables

✔️ Simple project to show how we used terraform variables

terraform plan -out=tfplan -var 'container_name=ghost_blog1' -var 'image_name=ghost:alpine' -var 'ext_port=8080'

terraform plan -out=tfplan -var 'container_name=ghost_blog1' -var 'image_name=ghost:alpine' -var 'ext_port=8080'