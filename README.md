# Progress

We need a local extension for Direccion Nacional de Vialidad Argentina (DNV) in which we can define the information about the progress of a contracting process:

* Progress

This extension will allow DNV to show more precise information about the progress been made during the contracting implementation.

## Worked example
The "progress" extension will be an object inside contracts, which mean that will be at the same level as amendments

```json
{
  "progress" : [ 
	{
		"advancePercentage" : 54.3,
		"investmentValue" : {
			"value" : {
				"amount" : 543000,
				"currency" : "ARS"
			}
		},
		"actualValue" : {
			"value" : {
				"amount" : 1000000,
				"currency" : "ARS"
			}
		}
	}
  ]
}

```
