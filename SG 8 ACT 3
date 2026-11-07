
class BankAccount:
    def __init__(self, account_number, balance):
        self._account_number = account_number
        self._balance = 0.0
        self.set_balance(balance)

    # Setter for account number
    def set_account_number(self, account_number):
        self._account_number = account_number

    # Setter for balance
    def set_balance(self, balance):
        if balance >= 0:
            self._balance = balance
        else:
            print("The balance must not be a negative number.")

    # Getter for account number
    @property
    def account_number(self):
        return self._account_number

    # Getter for balance
    @property
    def balance(self):
        return self._balance


# Create an object of BankAccount
a1 = BankAccount(12345, 1000)

print("Account 1")
print("Account Number:", a1.account_number)
print("Balance:", format(a1.balance, ".2f"))

# Update balance to a negative value
print("\nUpdate balance to -100")
a1.set_balance(-100)

print("Account Number:", a1.account_number)
print("Balance:", format(a1.balance, ".2f"))


