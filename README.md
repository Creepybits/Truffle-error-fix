# Truffle-error-fix
Fix for error mesasage "VM Exception while processing transaction: invalid opcode" while migrating contract.

![dep1](https://user-images.githubusercontent.com/60452756/120769341-51153580-c51d-11eb-8505-bfa3258aec68.PNG)


1. Close Ganache if you are using that.

2. Open a second terminal and run $ ganache-cli

![image](https://user-images.githubusercontent.com/60452756/120769756-b9641700-c51d-11eb-8a0c-02b4f2777121.png)

3. Make sure to have both terminals open, one with ganache-cli and the other where you make the migration.

4. Run $ truffle migrate in the second terminal. 

![image](https://user-images.githubusercontent.com/60452756/120770115-1a8bea80-c51e-11eb-8907-74d469308134.png)

Done!
