# demo-layered

## Reutilizando um Template Spring Boot em Outro Repositório

Você pode reutilizar um template de aplicação Spring Boot em outro repositório seguindo estes passos:

### 1. Clone o Repositório Original:

Clone o repositório que contém o template Spring Boot para o seu ambiente local.

```bash
git clone <URL_DO_REPOSITORIO_TEMPLATE>
```

### 2. Crie um Novo Repositório:

Crie um novo repositório no GitHub (ou em outra plataforma de hospedagem de código) onde você deseja usar o template.

### 3. Remova a Origem Antiga:

Remova a referência remota ao repositório original para evitar confusões.

```bash
git remote remove origin
```

### 4. Vincule ao Novo Repositório:

Vincule o repositório clonado ao novo repositório que você criou.

```bash
git remote add origin <URL_DO_NOVO_REPOSITORIO>
```

### 5. Empurre para o Novo Repositório:

Empurre as alterações para o novo repositório.

```bash
git push -u origin master
```

### 6. Personalize conforme Necessário:

Faça as personalizações necessárias no novo repositório, como ajustar o `README`, alterar o nome do projeto, etc.

Ao seguir esses passos, você terá reutilizado o template de aplicação Spring Boot em um novo repositório. Certifique-se de verificar e ajustar quaisquer configurações específicas do projeto ou referências ao antigo repositório para garantir que tudo funcione corretamente no novo contexto.
