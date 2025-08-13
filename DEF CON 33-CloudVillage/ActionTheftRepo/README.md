# Action Theft Repo

## Cloud Service Provider Used

AWS

## Story

HEXNOVA404 is a fast-growing security startup that was recently targeted in a mysterious breach. An attacker exploited a misconfigured GitHub Actions workflow to gain unauthorized access to sensitive AWS secrets. The attacker leveraged GitHub OIDC federation to assume an IAM role and retrieve credentials for another, more privileged role hidden inside AWS Secrets Manager.

To investigate and simulate the attack chain, the organization is now hiring skilled security researchers to retrace the adversary’s steps and uncover the final flag.

## Flag

FLAG-{5JyTnt31PIsnvsGJjQDvVWo82B0uSwwT}

## Points & Difficulty

Medium - 400

## Hints

xxx

## Services Used

1. AWS IAM
2. AWS S3
3. AWS Secrets Manager
4. GitHub Actions (OIDC federation)
5. Github gist

## Solution

Refer to the [solution/](./solution) directory.

## Implementation Details

xxx

## Additional Comments

xxx

## Contributor

- [Dhanush Nair](https://www.linkedin.com/in/dhn37/)
- [Jenko Hwong](https://www.linkedin.com/in/jenkohwong/)
- [Mike Ruth](https://www.linkedin.com/in/mrsec/)