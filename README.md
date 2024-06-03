Instalar Linux
Comandos:
ls: mostra o que tem na pasta
ll: descrição detalhado dor meus arquivos e pastas
cd: entra na pasta que estou escrevendo
cd ..: volta para a pasta
mkdir: criar pasta (ex: testlinux)
cd testlinux: abrir a pasta
tab: completa os nomes automaticamente
nano: criar ou editar um arquivo
comando --help: mostra as opções a usar (ex: -h)
cp nome_arquivo local_para_onde_quero_copiar: copia o arquivo e move para o local que quer colar
mv nome_do-arquivo nome_da_pasta: move pastas e tambem renomeia
cat nome_do_arquivo: mostra o que esta dentro do arquivo
cat nome_do_arquivo nome_do_arquivo > dar_novo_nome: Junta o que esta nos arquivos (ex: cat test1 test3 > test13)

rm: remove o arquivo total
rm nome_do_arquivo com *: remove todos arquivos com nome igual do * (ex: rm test*)
rm nome_da_pasta -r: remove arquivos e pastas (ex: rm testado/ -r)

head nome_do_arquivo: mostra o inicio do arquivo (ex: head test20)
tail nome_do-arquivo: mostra o fim do aruqivo (ex: tail test20)

Contagem de itens do arquivo: wc
wc -l nome_do-arquivo: mostra o número de linhas 
wc -w nome_do-arquivo: mostra o número de palavras
wc -c nome_do-arquivo: mostra o número de caracteres.

ls | wc -l: mostra quantos arquivos e pastas tenho.

grep -iE (nome da espressão) nome_do-arquivo: procura exatamente a espressão ou item dentro do arquivo (ex grep -iE não test20)
grep -iE error *log: procurar errors em todos arquivos terminados em log. 

tar -czvf test.tar.gz nomes_dos-arquivos*: Compactar arquivos 
tar -xzvf nomes_do_arquivo_compactado: Descompactar arquivo (ex: tar -xzvf test.tar.gz)
zcat nome_do_arquivo_compactado: Mostra o que tem dentro do arquivo
zgrep nome_do_arquivo_compactado: acha um item dentro do aruqivo compactado. 

du -h: mostra quantos gigas usei 
-h: em humano

sftp: envia ou transfere arquivos do windows PowerShell para o servidor do Linux.
mput test: enviar para edna
get: para buscar do Edna
