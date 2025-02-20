## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_terraform"></a> [terraform](#requirement\_terraform) | >= 0.13.0 |

## Providers

| Name | Version |
|------|---------|
| <a name="provider_google"></a> [google](#provider\_google) | n/a |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [google_compute_instance.default](https://registry.terraform.io/providers/hashicorp/google/latest/docs/resources/compute_instance) | resource |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_instance_image"></a> [instance\_image](#input\_instance\_image) | Nome da inst├óncia na Google Cloud | `string` | n/a | yes |
| <a name="input_instance_name"></a> [instance\_name](#input\_instance\_name) | Nome da inst├óncia na Google Cloud | `string` | n/a | yes |
| <a name="input_labels"></a> [labels](#input\_labels) | Lista de labels para nossa inst├óncia maneira | `map(string)` | n/a | yes |
| <a name="input_machine_type"></a> [machine\_type](#input\_machine\_type) | Tipo de m├íquina na Google Cloud | `string` | n/a | yes |
| <a name="input_network"></a> [network](#input\_network) | Nome da rede existente na GCP | `string` | n/a | yes |
| <a name="input_project"></a> [project](#input\_project) | Nome do projeto existente na Google Cloud | `string` | n/a | yes |
| <a name="input_subnetwork"></a> [subnetwork](#input\_subnetwork) | Nome da subrede existente na GCP * foi definido o valor padr├úo para caso passe a NETWORK com o valor 'default' | `string` | `""` | no |
| <a name="input_zone"></a> [zone](#input\_zone) | Zona na Google Cloud | `string` | n/a | yes |

## Outputs

No outputs.
