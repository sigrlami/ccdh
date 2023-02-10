# CONCORDIUM HACKATON - TASK 3 - SUBMISSION

Mainnet address: 4csBZDoBmhtMmsq4dWTGdWowT7RMZtJJrEQGF5XHUKbuG4vAdZ

- Task1: https://github.com/sigrlami/ccdh/blob/sb/ccdh-task-1-submission/README.md
- Task2: https://github.com/sigrlami/ccdh/tree/sb/ccdh-task-2-submission

This is simple dAPP implemented in Elm which allows to create tourist routes that are stored on-chain. Available here [trails.ccd.sigrlami.eu](https://trails.ccd.sigrlami.eu)


![demo](media/demo.gif)

![demo](media/screen-1.png)


## Structure

- `app/frontend` - source code for Elm frontend that uses Javascript SDK for Concordium
- `contracts` - source code for Concordium smart-contracts that store data on-chain
- `media` - additional media files for better presentation

## Details

App can be viewable in 2 ways:

- `simple`   - (as shown in demo), allows to add and change data
- `extended` - visualize on-chain data
