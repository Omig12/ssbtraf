# Sbot Usage


## Whoami 

```sh
$ sbot whoami

{
  "id": "@RDRnDaZhV5Yg1NWAN78D04iZtJ8hWrQoT5iBJfYcIpg=.ed25519"
}
```

## Get Message
```sh
$ sbot get "%hTvQp59Xzzr0+1h52Np9tHZ70ZhYA3xzmJ+3qS1T6Mc=.sha256"
{
  "previous": "%ZmCXOJYeinxoM30QnI77rdjGGtcIjztr2AOx7rL2+Ww=.sha256",
  "author": "@RDRnDaZhV5Yg1NWAN78D04iZtJ8hWrQoT5iBJfYcIpg=.ed25519",
  "sequence": 204,
  "timestamp": 1523544505980,
  "hash": "sha256",
  "content": "fk2vWk+yeFbn0dAoBtHSINpHjdyFyZ9S5MuhbJbN7HyAs3ANK1Hshhc3wo60FjyS7iW+wovvCBFomT60PCLHDeFL2YpOyqsmVan0+H1l3utbNivil/rjEGf56tkZISe7xeV2bKjRtR7qflHi+KHnQTzC/FfO1YR0JV1M1CAF+UvT5I9i+Koc8AlJGJTasfn+RYaCw/NGKhQb0Gt/ZGvKjUScmCFnRlTeKSywdxvaxG54TQjHTIMw7qAONdMao6B2OYiXDHmz+4IY409hFLoZeJR3oGhOrU/HyzBHp5DG5Y7eeFbFt/kjtqP5s8+5+Iw7EX8k3qn/BcnFLvNNAdynjfwTZ2++OcB4rpzcDSTjKr4QMvKTWNvCSOagGDoVUo0XKEEwUAJX7KtqRo4EsSRaCiCxUgRpmMX8qkmKJ/EPxcx7Wr6a/B4TVS1ZzWvIpubvhpfWhaC7SlivgXGdVNOIQ6A4ONzuGELtEJ/tuLXEamGk2AAmlEurqd4u2Rsgtg14GRc4Kmjvj6Oss1l0X7BYX3MwsMuLuOk9oUcHqTX3T6RKsNhy4NCHAz16poCRJeRpu9+PfOxVOP7zIG/X1pbeGsIP3Of2KRjy/Rpdx7w3BZ0YzaHDWUZRrXLEuBcx6vkP9SRnDgEiMX0OiIytOZqAvW0l2WNAlzOAQup3GVi63Xql5F3hvOr4ndSg2XqgHzKgrjgPLRKSPXsDuDGorxCQVm+kf5mEJKc4d8lncuhfQjIIGKXy7bMJnz78YpzIypCeZLgN0FcyIbXSgVv/80+IDYKELuYFCiHo6Q3kJoUMgYKkEELkkNYnHw0rbNp9b29EFv6v3jk6MvvbNrwna0hxU0HPf+eOjLtXU1Cuth9csSvoN7/7sqvsnmeCVyyILk6u99qAe2aeZNbBfUikeU8iA5lTYrTWPidJBEm0RAS2zekZmZ9CdvbhQALAeH+t5jaMCalSOZKUD83V6P8ePa9DHzqIJlxYIuef0e72y4c6IElgkosg0YufFUR9gRqYc5euJBCpe3IunOB3AKqklyDaDDE8NvqRRWvDAfPl8b8/Uki9jXt59skDMMfldKgXpjbY16++96zKear+M3RFKTFPM6Xq/Etyiqr2NsF/nq5W3k0GY/O5zLeS/FQmAaMKY0aiez+JRjMJeDVgnotjLPhp2xr6drQHhK6ATub4NIc8SqQ2weM0jyUEbgUjQ0xb1U6j+UW5ODXPYaNqadOL1X9SKddajw2IYPjl5lNKNNiR2f36nV8dqHGzq72hF/ijOAzMYh3LgKMFJ4csdrGG1D5Tsb8gGcdeDD6+3O/GsWbnFJHfCq2cWEd6Va9bX1yucHeV6msvO2beMRQSgLFQeVp3wWY4LFN9KRQr7veAc+4tnVTwtLMd8uDV+sUsa10tsH5kcI+KjR3tYytv/Lfv0doWmuxouNWSuZU=.box",
  "signature": "nbsBcftJGC+x1cIBMSNFOTag5KfN31JS0uyias7scK7UBCmA0m8JLgikjLrs8YCvGaWE98cw9PoJkFvO4UVJDw==.sig.ed25519"
}
```


## Private Box
```sh
$ sbot private.unbox "hTvQp59Xzzr0+1h52Np9tHZ70ZhYA3xzmJ+3qS1T6Mc=.sha256"
```

## Create User stream
```sh
$ sbot createUserStream --id "@RDRnDaZhV5Yg1NWAN78D04iZtJ8hWrQoT5iBJfYcIpg=.ed25519"
{
  "key": "%ZP5zJW5R86yADxBBmJaxqd/TFjEtA6yWivaqC1uAdQE=.sha256",
  "value": {
    "previous": null,
    "author": "@RDRnDaZhV5Yg1NWAN78D04iZtJ8hWrQoT5iBJfYcIpg=.ed25519",
    "sequence": 1,
    "timestamp": 1516107712440,
    "hash": "sha256",
    "content": {
      "type": "about",
      "about": "@RDRnDaZhV5Yg1NWAN78D04iZtJ8hWrQoT5iBJfYcIpg=.ed25519",
      "image": "&Ih+ZIBKLrLQYM+LZRtPM4QpuIrsTiVdIvh+Gb0xyGjQ=.sha256",
      "name": "Omig12",
      "description": "Hi! I'm a senior computer science student at the University of Puerto Rico and a FOSSH enthusiast."
    },
    "signature": "0GEyvxv144aeTUfJnNCiBq+2SosB9jznqUsfQS79u1FLAm+aGDu4c4AtMjzQAgErNurs0cXXXz1ypkns5155Ag==.sig.ed25519"
  },
  "timestamp": 1516107712485
}
 .
 .
 .
 .
 . 
{
  "key": "%hTvQp59Xzzr0+1h52Np9tHZ70ZhYA3xzmJ+3qS1T6Mc=.sha256",
  "value": {
    "previous": "%ZmCXOJYeinxoM30QnI77rdjGGtcIjztr2AOx7rL2+Ww=.sha256",
    "author": "@RDRnDaZhV5Yg1NWAN78D04iZtJ8hWrQoT5iBJfYcIpg=.ed25519",
    "sequence": 204,
    "timestamp": 1523544505980,
    "hash": "sha256",
    "content": "fk2vWk+yeFbn0dAoBtHSINpHjdyFyZ9S5MuhbJbN7HyAs3ANK1Hshhc3wo60FjyS7iW+wovvCBFomT60PCLHDeFL2YpOyqsmVan0+H1l3utbNivil/rjEGf56tkZISe7xeV2bKjRtR7qflHi+KHnQTzC/FfO1YR0JV1M1CAF+UvT5I9i+Koc8AlJGJTasfn+RYaCw/NGKhQb0Gt/ZGvKjUScmCFnRlTeKSywdxvaxG54TQjHTIMw7qAONdMao6B2OYiXDHmz+4IY409hFLoZeJR3oGhOrU/HyzBHp5DG5Y7eeFbFt/kjtqP5s8+5+Iw7EX8k3qn/BcnFLvNNAdynjfwTZ2++OcB4rpzcDSTjKr4QMvKTWNvCSOagGDoVUo0XKEEwUAJX7KtqRo4EsSRaCiCxUgRpmMX8qkmKJ/EPxcx7Wr6a/B4TVS1ZzWvIpubvhpfWhaC7SlivgXGdVNOIQ6A4ONzuGELtEJ/tuLXEamGk2AAmlEurqd4u2Rsgtg14GRc4Kmjvj6Oss1l0X7BYX3MwsMuLuOk9oUcHqTX3T6RKsNhy4NCHAz16poCRJeRpu9+PfOxVOP7zIG/X1pbeGsIP3Of2KRjy/Rpdx7w3BZ0YzaHDWUZRrXLEuBcx6vkP9SRnDgEiMX0OiIytOZqAvW0l2WNAlzOAQup3GVi63Xql5F3hvOr4ndSg2XqgHzKgrjgPLRKSPXsDuDGorxCQVm+kf5mEJKc4d8lncuhfQjIIGKXy7bMJnz78YpzIypCeZLgN0FcyIbXSgVv/80+IDYKELuYFCiHo6Q3kJoUMgYKkEELkkNYnHw0rbNp9b29EFv6v3jk6MvvbNrwna0hxU0HPf+eOjLtXU1Cuth9csSvoN7/7sqvsnmeCVyyILk6u99qAe2aeZNbBfUikeU8iA5lTYrTWPidJBEm0RAS2zekZmZ9CdvbhQALAeH+t5jaMCalSOZKUD83V6P8ePa9DHzqIJlxYIuef0e72y4c6IElgkosg0YufFUR9gRqYc5euJBCpe3IunOB3AKqklyDaDDE8NvqRRWvDAfPl8b8/Uki9jXt59skDMMfldKgXpjbY16++96zKear+M3RFKTFPM6Xq/Etyiqr2NsF/nq5W3k0GY/O5zLeS/FQmAaMKY0aiez+JRjMJeDVgnotjLPhp2xr6drQHhK6ATub4NIc8SqQ2weM0jyUEbgUjQ0xb1U6j+UW5ODXPYaNqadOL1X9SKddajw2IYPjl5lNKNNiR2f36nV8dqHGzq72hF/ijOAzMYh3LgKMFJ4csdrGG1D5Tsb8gGcdeDD6+3O/GsWbnFJHfCq2cWEd6Va9bX1yucHeV6msvO2beMRQSgLFQeVp3wWY4LFN9KRQr7veAc+4tnVTwtLMd8uDV+sUsa10tsH5kcI+KjR3tYytv/Lfv0doWmuxouNWSuZU=.box",
    "signature": "nbsBcftJGC+x1cIBMSNFOTag5KfN31JS0uyias7scK7UBCmA0m8JLgikjLrs8YCvGaWE98cw9PoJkFvO4UVJDw==.sig.ed25519"
  },
  "timestamp": 1523544506025
}
```

## Convert Timestamp to date
```sh
$ echo "console.log(new Date(1523544506025).toLocaleString());" | node
```

## Get specific Message
```sh
$ sbot get "%hTvQp59Xzzr0+1h52Np9tHZ70ZhYA3xzmJ+3qS1T6Mc=.sha256"
```

## Unhash a .box message
```sh
$ sbot private.unbox "fk2vWk+yeFbn0dAoBtHSINpHjdyFyZ9S5MuhbJbN7HyAs3ANK1Hshhc3wo60FjyS7iW+wovvCBFomT60PCLHDeFL2YpOyqsmVan0+H1l3utbNivil/rjEGf56tkZISe7xeV2bKjRtR7qflHi+KHnQTzC/FfO1YR0JV1M1CAF+UvT5I9i+Koc8AlJGJTasfn+RYaCw/NGKhQb0Gt/ZGvKjUScmCFnRlTeKSywdxvaxG54TQjHTIMw7qAONdMao6B2OYiXDHmz+4IY409hFLoZeJR3oGhOrU/HyzBHp5DG5Y7eeFbFt/kjtqP5s8+5+Iw7EX8k3qn/BcnFLvNNAdynjfwTZ2++OcB4rpzcDSTjKr4QMvKTWNvCSOagGDoVUo0XKEEwUAJX7KtqRo4EsSRaCiCxUgRpmMX8qkmKJ/EPxcx7Wr6a/B4TVS1ZzWvIpubvhpfWhaC7SlivgXGdVNOIQ6A4ONzuGELtEJ/tuLXEamGk2AAmlEurqd4u2Rsgtg14GRc4Kmjvj6Oss1l0X7BYX3MwsMuLuOk9oUcHqTX3T6RKsNhy4NCHAz16poCRJeRpu9+PfOxVOP7zIG/X1pbeGsIP3Of2KRjy/Rpdx7w3BZ0YzaHDWUZRrXLEuBcx6vkP9SRnDgEiMX0OiIytOZqAvW0l2WNAlzOAQup3GVi63Xql5F3hvOr4ndSg2XqgHzKgrjgPLRKSPXsDuDGorxCQVm+kf5mEJKc4d8lncuhfQjIIGKXy7bMJnz78YpzIypCeZLgN0FcyIbXSgVv/80+IDYKELuYFCiHo6Q3kJoUMgYKkEELkkNYnHw0rbNp9b29EFv6v3jk6MvvbNrwna0hxU0HPf+eOjLtXU1Cuth9csSvoN7/7sqvsnmeCVyyILk6u99qAe2aeZNbBfUikeU8iA5lTYrTWPidJBEm0RAS2zekZmZ9CdvbhQALAeH+t5jaMCalSOZKUD83V6P8ePa9DHzqIJlxYIuef0e72y4c6IElgkosg0YufFUR9gRqYc5euJBCpe3IunOB3AKqklyDaDDE8NvqRRWvDAfPl8b8/Uki9jXt59skDMMfldKgXpjbY16++96zKear+M3RFKTFPM6Xq/Etyiqr2NsF/nq5W3k0GY/O5zLeS/FQmAaMKY0aiez+JRjMJeDVgnotjLPhp2xr6drQHhK6ATub4NIc8SqQ2weM0jyUEbgUjQ0xb1U6j+UW5ODXPYaNqadOL1X9SKddajw2IYPjl5lNKNNiR2f36nV8dqHGzq72hF/ijOAzMYh3LgKMFJ4csdrGG1D5Tsb8gGcdeDD6+3O/GsWbnFJHfCq2cWEd6Va9bX1yucHeV6msvO2beMRQSgLFQeVp3wWY4LFN9KRQr7veAc+4tnVTwtLMd8uDV+sUsa10tsH5kcI+KjR3tYytv/Lfv0doWmuxouNWSuZU=.box"
{
  "type": "post",
  "text": "[@Humberto Ortiz Zuazaga](@RtsOc2h1gqh0fRrjrUTHAkRBu9YyDgsD+EWsfLpykrc=.ed25519)\n\nWhat is are Fourier Transforms anyway?\n\nIt's a series of discrete adaptations of the complex Fourier Series, that allow us to observe functions of the frequencies of participation of certain elements or changes on a signal over a continuous amount time. This is done by converting the continuous time signal into discrete intervals, and then treating the discrete interval as a group of frequency measurements, resulting in series of frequencies measurements over a the length of the signal, effectively decomposing the signal into the frequency of it's components. ",
  "mentions": [
    {
      "link": "@RtsOc2h1gqh0fRrjrUTHAkRBu9YyDgsD+EWsfLpykrc=.ed25519",
      "name": "Humberto Ortiz Zuazaga"
    }
  ],
  "recps": [
    "@RDRnDaZhV5Yg1NWAN78D04iZtJ8hWrQoT5iBJfYcIpg=.ed25519",
    "@RtsOc2h1gqh0fRrjrUTHAkRBu9YyDgsD+EWsfLpykrc=.ed25519"
  ]
}
```

##
```sh
$ sbot friends.get 
```


### Research Questions:
* Given that I know the author of the message can I factor out public key from the hash?
  - Answer is no senders public/private key is turned into an eliptic curve which is then in turn hashed with a random 32-bit key, so knowing the public key of the sender is not enough.
* If an author sends the same message to multiple people at the same time could I calculate the difference between the different hashes?
  - It is all enclosed within one big private box, and a set of hashings of a shared super key for each different private key of each recipient.
* Can I tell where each hash for the super key and the final header starts?
  - Not sure yet. 

	
