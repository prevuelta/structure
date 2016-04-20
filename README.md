## Measure
A quick tool for creating a measure.scss file that includes unit & proportional unit measurements, divisions and multiplications to be used in sass layout / typography.

eg output:

```
/*
*   STRUCTURE VARIABLES
*   Generated Wed Apr 20 2016 12:27:59 GMT+1200 (NZST)
*/

/*
*   Units
*/

$u: 12px;

/* Unit divisions */

$hu: $u * 0.5;
$qu: $u * 0.25;
$qqqu: $u * 0.75;
$tu: $u * 0.3333333333333333;
$ttu: $u * 0.6666666666666666;

/* Unit multiplications */

$uh: $u * 1.5;
$u2: $u * 2;
$u3: $u * 3;
$u4: $u * 4;
$u5: $u * 5;
$u6: $u * 6;
$u7: $u * 7;
$u8: $u * 8;
$u9: $u * 9;
$u10: $u * 10;

/*
*   Proportional units
*/

$pu: 1rem;

/* Proportional unit divisions */

$phu: $u * 0.5;
$pqu: $u * 0.25;
$pqqqu: $u * 0.75;
$ptu: $u * 0.3333333333333333;
$pttu: $u * 0.6666666666666666;

/* Proportional unit multiplications */

$puh: $pu * 1.5;
$pu2: $u * 2;
$pu3: $u * 3;
$pu4: $u * 4;
$pu5: $u * 5;
$pu6: $u * 6;
$pu7: $u * 7;
$pu8: $u * 8;
$pu9: $u * 9;
$pu10: $u * 10;

/* Misc measurements */

$golden_ratio: (1+sqrt(5))/2;
$silver_ratio: sqrt(2);
```