# 5xx

<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
## Requirements

No requirements.

## Providers

| Name | Version |
|------|---------|
| <a name="provider_aws"></a> [aws](#provider\_aws) | n/a |

## Modules

| Name | Source | Version |
|------|--------|---------|
| <a name="module_base"></a> [base](#module\_base) | ../../base | n/a |

## Resources

| Name | Type |
|------|------|
| [aws_alb.balancer](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/data-sources/alb) | data source |
| [aws_region.current](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/data-sources/region) | data source |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_balancer"></a> [balancer](#input\_balancer) | n/a | `string` | n/a | yes |
| <a name="input_coordinates"></a> [coordinates](#input\_coordinates) | position | <pre>object({<br>    x : number<br>    y : number<br>    width : number<br>    height : number<br>  })</pre> | n/a | yes |
| <a name="input_period"></a> [period](#input\_period) | n/a | `number` | `300` | no |
| <a name="input_region"></a> [region](#input\_region) | region | `string` | `""` | no |
| <a name="input_stat"></a> [stat](#input\_stat) | stats | `string` | `"Average"` | no |

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_data"></a> [data](#output\_data) | n/a |
<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
