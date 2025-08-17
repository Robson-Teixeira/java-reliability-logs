## Instalações
- [Docker Desktop](https://docs.docker.com/desktop/install/windows-install/)
- [WSL](https://learn.microsoft.com/pt-br/windows/wsl/install)
- [Docker Compose](https://docs.docker.com/compose/install/)
- [Maven](https://maven.apache.org/install.html)
- [Java](https://www.oracle.com/java/technologies/downloads/)
  - [JDK 11](https://www.oracle.com/br/java/technologies/javase/jdk11-archive-downloads.html)
- IDE ([IntelliJ](https://www.jetbrains.com/pt-br/idea/#), [Eclipse](https://eclipseide.org/), etc.)

## Documentação
- [Simple Logging Facade for Java - SLF4J](https://www.slf4j.org/)

## Definições
- `Backlog` é a API de logging
- Níveis de log
  - `TRACE`: Fornece o nível mais detalhado de informações de log. Usado para rastrear a execução do código passo a passo e diagnosticar problemas complexos.
  - `DEBUG`: Usado para registrar informações detalhadas que são úteis durante o desenvolvimento e depuração.
  - `INFO`: Registra informações gerais sobre o progresso do aplicativo.
  - `WARN`: Indica uma situação potencialmente prejudicial que pode causar problemas.
  - `ERROR`: Registra erros graves que impedem o funcionamento correto de uma funcionalidade.
  - `FATAL`: Designa erros muito graves que provavelmente levarão ao encerramento do aplicativo. Não disponível para uso durante o desenvolvimento.