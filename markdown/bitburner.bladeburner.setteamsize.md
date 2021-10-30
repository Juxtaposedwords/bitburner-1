<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bitburner](./bitburner.md) &gt; [Bladeburner](./bitburner.bladeburner.md) &gt; [setTeamSize](./bitburner.bladeburner.setteamsize.md)

## Bladeburner.setTeamSize() method

You have to be employed in the Bladeburner division and be in BitNode-7 or have Source-File 7 in order to use this function.

Set the team size for the specified Bladeburner action.

Returns the team size that was set, or -1 if the function failed.

<b>Signature:</b>

```typescript
setTeamSize(
    type: BladeburnerActTypes,
    name: BladeburnerGenActions | BladeburnerContracts | BladeburnerOperations | BladeburnerBlackOps,
    size: number,
  ): number;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  type | [BladeburnerActTypes](./bitburner.bladeburneracttypes.md) | Type of action. |
|  name | [BladeburnerGenActions](./bitburner.bladeburnergenactions.md) \| [BladeburnerContracts](./bitburner.bladeburnercontracts.md) \| [BladeburnerOperations](./bitburner.bladeburneroperations.md) \| [BladeburnerBlackOps](./bitburner.bladeburnerblackops.md) | Name of action. Must be an exact match. |
|  size | number | Number of team members to set. Will be converted using Math.round(). |

<b>Returns:</b>

number

Number of Bladeburner team members you assigned to the specified action.

## Remarks

4 GB
