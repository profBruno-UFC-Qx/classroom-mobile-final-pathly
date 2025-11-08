[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/AR7CADm8)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=21516424)
# Proposta de aplicativo

## Equipe
* **Nome do Aluno(a):** George Felipe Placido Nogueira - 548348

---

## Título do Projeto
Pathly: Seu Diário Pessoal de Viagens e Memórias

## Descrição do Projeto
Pathly é um aplicativo móvel Android, desenvolvido inteiramente em Kotlin e Jetpack Compose, que funciona como um diário de viagens e memórias. O projeto nasce para resolver o problema de memórias de locais visitados que se perdem em rolos de câmera, aplicativos de notas e na própria memória. Muitas vezes, lembramos de um lugar incrível que visitamos, mas não conseguimos juntar facilmente a foto que tiramos, a localização exata e o sentimento daquele momento.

O público-alvo são viajantes, exploradores urbanos ou simplesmente pessoas que gostam de catalogar suas experiências e locais favoritos. O Pathly centraliza tudo isso: o usuário pode criar um novo "registro", anexar uma foto (seja tirada na hora ou da galeria), capturar as coordenadas exatas com o GPS e adicionar notas. O aplicativo salva tudo em um banco de dados local (Room) para acesso offline e, para adicionar contexto, busca o clima atual daquela localização usando uma API externa (OpenWeatherMap).

---

## Funcionalidades Principais
[Liste as principais funcionalidades do projeto. Use caixas de seleção para que a equipe possa marcar as concluídas nas próximas etapas.]

- [ ] CRUD: Permitirá o usuário a criar, ler, atualizar e deletar memórias de locais.
- [ ] Salvar Registros: Salvar todos os registros permanentemente no banco de dados local.
- [ ] Localização: Capturar a localização exata (Latitude/Longitude) via GPS ao adicionar um novo local.
- [ ] Anexar Fotos: Anexar uma foto personalizada para cada local, utilizando a Câmera ou a Galeria do dispositivo.
- [ ] Exibir Clima: Buscar e exibir o clima atual do local salvo (via integração com API OpenWeatherMap).
- [ ] Navegação de telas: Implementar navegação entre a tela de lista, tela de detalhes e tela de adição/edição.
- [ ] Temas Dark e Light: Suporte completo a tema claro e escuro (MaterialTheme).
---

> [!WARNING]
> Daqui em diante o README.md só deve ser preenchido no momento da entrega final.

##  Tecnologias: 
Liste aqui as tecnologias e bibliotecas que foram utilizadas no projeto.

---

## Instruções para Execução
[Inclua instruções claras sobre como rodar o projeto localmente. Isso é crucial para que você possa testá-lo nas próximas entregas. **Somente caso haja alguma coisa diferente do usual**

```bash
# Clone o repositório
git clone [https://docs.github.com/pt/repositories/creating-and-managing-repositories/about-repositories](https://docs.github.com/pt/repositories/creating-and-managing-repositories/about-repositories)

# Navegue para o diretório
cd [nome-do-repositorio]

# Siga as instruções específicas para a sua tecnologia...
