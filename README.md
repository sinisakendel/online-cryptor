# online-cryptor


## Algo
AES 256 CBC

## OpenSSL command lines

    printf "Lorem ipsum dolor sit amet, ..." | \
    openssl enc -e -base64 -A -aes-256-cbc -pass pass:"my-password"

    printf "U2FsdGVkX1/l/LqNSCQixd0iPv4neKAGZvbQDbYUovZE4OcM7l3ULNDgkZQmrweN" | \
    openssl enc -d -base64 -A -aes-256-cbc -pass pass:"my-password"