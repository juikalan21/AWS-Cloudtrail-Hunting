# AWS-Cloudtrail-Hunting

## Hypothesis:
1. Bruteforcing weak authentication for AWS Console.
2. Root access through console.
3. An adversary may disrupt trails in an attempt to evade defenses.
4. An adversary may attempt to retrieve secrets from secret manager - steal certificates, sensitive data.
5. Attacker Created permanent IAM key/user.

## Dataset
Cloudtrail logs from AWS account

## Offensive Tradecraft
Attacker may try to get access into a loose AWS account and perform damage to steal credential or data. It can also maintain a persistance by creating additional role/user.
