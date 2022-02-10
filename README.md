# Take Control of Your Data by Integrating Hashicorp Vault

Dealing with data is not a trivial matter. It gets even more complicated when this is spread across multiple Cloud Providers or on-premises resources. How do you ensure you have an easily accessible copy in the event of a primary data failure?

## Suppose you wanted to address the issue. How would you?

We went ahead and designed a strategy, a set of best practices that can be leveraged to implement a multiple layers solution, tailored  to our needs, which will mitigate the risk and ease operations.

![Strategy](./hashitalk_2022_strategy.svg)


## Building blocks
* [Restic](https://restic.net/)
* [Ansible](https://www.ansible.com/)
* [Vault](https://www.vaultproject.io/)

## To sum up
What we have described here is an End-to-End Encrypted Backup & Recovery Solution leveraging Vault capabilities. This is a self managed approach which will work in a hybrid environment. 
