DEHY
====

Dehydration Stage

## Format

Count | Subrecord | Name | Type | Info
------|-----------|------|------|-----
+ | EDID | Editor ID | cstring |
+ | DATA | Data | struct |

### DATA

Name | Type | Info
-----|------|-----
Trigger Threshold | uint32 |
Actor Effect | formid | FormID of a [SPEL](SPEL.md) record.
