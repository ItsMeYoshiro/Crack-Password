# Crack-Password
Cracker de senhas utilizando Shell.
Algoritmos aceitos: base64, md5, shal, sha256, sha512.

# Uso
Uso: ./crack_password.sh

## OPÇÕES
    
-h, --help\t\t\t Exibe este menu de ajuda.
-v, --version\t\t Versão do programa.
-H, --hash\t\t\t Hash a ser quebrado.
-a, --alg\t\t\t Recebe o nome do algoritmo de criptografia.
-w, --wordlist\t\t Recebe um arquivo contendo uma lista de senhas.

## Exemplo:
./crack_password.sh -h
./crack_password.sh -v
./crack_password.sh -a base64 -H hash ===> HASHs no formato BASE64 não precisam de wordlist
./crack_password.sh -a md5 -H hash -w wordlist.txt
./crack_password.sh -a shal -H hash -w wordlist.txt
