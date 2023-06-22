# Algorand Developer Workshop
Sign up for future sessions on the Algorand Developer Portal Events page: [https://developer.algorand.org/events](https://developer.algorand.org/events)

## Gitpod link
Get started working on this repo in Gitpod without needing to setup local environment. A gitpod account is required, so sign-in with your Github to get started.

https://gitpod.io/#https://github.com/algorand-devrel/workshop

## Building with AlgoKit on Gitpod

- 1. open new terminal
- 2. run `algokit init`
- 3. select "playground"
- 4. name your project "pg1" or similar
- 5. answer (Y)es to accept the defaults
- 6. a new Gitpod window opens at `/workspace/workshop/pg1`
- 7. review `pg1/hello_world/helloworld.py`
- 8. select "Run & Debug" from left nav
- 9. run `algokit localnet start`
- 10. click green arrow to "Demo current contract (+ Localnet)
- 11. contract is compiled, installed and demo executed on CLI
- 12. review files in `pg1/hello_world/artifacts`
- 13. select "application.json" right click to download
- 14. run `algokit localnet explore`
- 15. a new browser window launches into dAppFlow
- 16. click "Dev Wallets" from left nav
- 17. click "Create wallet" (100A automatically dispensed)
- 18. click "Connect wallet" (now connected to your account)
- 19. click "Beaker Studio" from left nav
- 20. click "Select app" then "Import Beaker app"
- 21. from the "File" tab click "Upload file" and select application.json from step 13
- 22. review application contents
- 23. click "Create app" from top nav, then "Create"
- 24. notice the "App ID" in top nav
- 25. scroll to ABI section, review methods
- 26. click "Execute" for the "hello" method
- 27. noice the required arguments and their types, enter a value for "name" then click "Execute"
- 28. review the response "Hello, AlgoDev"

## Video Recordings
- Episode #1 [Hello, AlgoDevs](https://youtu.be/KX7Vo_TeE9M)
- Episode #2 Building with AlgoKit, PyTeal and Beaker
