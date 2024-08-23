### Workshop
first workshop- Transaction id: at185af3qc4g08guacw7chj0r2alhj0pedfrrp3k5h39k9vzajfsvyseduet6
second workshop- Transaction id: at1ceuvh7wwr3wh3yzar272u8r4kzxxnznj66kl4lx86usjsnxj0ggq7wpqad
third workshop- Transaction id: at1mccwppsdk8szqsqcduhy29s49t8ue2552c99ngjnk8feuf54vcgs74fnwp
## preview ![image](https://github.com/user-attachments/assets/e6402807-a749-45d0-9986-53c98929ef48)
## description

# First Workshop
Command: `leo run main 3u32 2u32 --network testnet`
Where main = transition function name, `3u32 2u32` is the inputs and network is specified `testnet`
I deploy using demo.leo.app
`generated private key in my.env needs to be change to that of your Leo wallet private key` for it to be deployed without error

# Second Workshop
For the second workshop

1st Command : `leo run mint <type_aleo_address> <type_amount>u64`
Record were generated from simple token (build and src files) were copied to my token file in order for the deployment to be successful.
 `generated private key in my.env needs to be change to that of your Leo wallet private key` for it to be deployed without errors.
 
2nd command: `leo run transfer "<Token_Record>" <to_address> <amount>u64`
The generated record from the 1st command were input into the second command's first input and then address and amount.
`generated private key in my.env needs to be change to that of your Leo wallet private key` for it to be deployed without errors.
# Third Workshop
Command: `leo run combine_hash_owner_receiver <type_your_address> <type_friend_address>`
This has only 2 inputs where first input is owner address (self.caller) and second input is the  receiver address.
`generated private key in my.env needs to be change to that of your Leo wallet private key` for it to be deployed without errors.
