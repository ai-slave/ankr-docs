import { Callout } from "components";

# Contract automation
Ankr Automation enables you to execute your contract functions based on various triggers.
It is an automation platform that uses the same decentralized node infrastructure that made Ankr so well-known and popular in crypto.
Building with Ankr Automation will help you get to market faster and save you time and money on setup, maintenance, and risk costs.

## Available triggers
Ankr Automation will execute smart contract functions based on various triggers.

* Time-based triggers, allowing you to execute a contract function on a schedule of your choice. Your contract doesn't need to be compatible with `AutomationInterface`.
* Custom logic triggers, allowing you to execute a contract function on a certain event. Your contract needs to be compatible with `AutomationInterface`.

### Time-based trigger
Use it when you need to execute a contract function at a certain time.
You can set date and time via conventional drop-down lists or write a CRON expression.

First, deploy the contract you want to automate. Your contract doesn't need to be compatible with `AutomationInterface`.
If your contract isn't verified, you will need the ABI for it.

1. Open [Ankr Automation Dashboard](https://www.ankr.com/automate/dashboard/).
2. Connect your wallet and switch to a supported network.
3. **Create Task** and select **Time-based trigger**. Set a name, provide the address of your deployed contract, provide the ABI if the contract isn't verified, and choose a function to execute. 
4. Set the schedule via the drop-down list or a CRON expression.
5. Complete the remaining details.
6. Top up your account to meet the gas fee costs. 

You can manage created Tasks from [Ankr Automation Dashboard](https://www.ankr.com/automate/dashboard/).

### Custom logic trigger
Use it when you need to execute a contract function on a certain event. 

First, deploy the contract you want to automate. Your contract needs to be compatible with `IAutomateCompatible`.

1. Open [Ankr Automation Dashboard](https://www.ankr.com/automate/dashboard/).
2. Connect your wallet and switch to a supported network.
3. **Create Task** and select **Custom logic trigger**. Set a name, provide the address of your deployed contract, choose a function to execute and provide the custom logic on when to execute that function.
5. Complete the remaining details.
6. Top up your account to meet the gas fee costs. 

You can manage created Tasks from [Ankr Automation Dashboard](https://www.ankr.com/automate/dashboard/).

## Supported networks
Ankr Automation supports BNB Smart Chain. Support for other networks is coming soon. 

## Next read 
* [Time-based automation](/automation/time-based-automation/)
* [Custom logic automation](/automation/custom-logic-automation/)
* [Manage automation tasks](/automation/manage-tasks)
* [Create compatible contracts](/automation/create-compatible-contracts/)



