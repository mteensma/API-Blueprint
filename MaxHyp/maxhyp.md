FORMAT: 1A

# MaxHyp

The MaxHyp API allows for calculating the maximum mortgage amount

## Maximum Mortgae Amount [/mortgages/max-loan-amount]

### Caculate the amount [GET]

+ Response 200 (application/json)

  + attributes (object)

    + amount: (number) - the calculated amount
    + date: (date) - date untill the calculated amount remains valid

  - body
    {
      "amount" : Null
    }
