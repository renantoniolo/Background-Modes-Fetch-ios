# Background Modes (Fetch)
 Permite o aplicativo fazer algumas tarefas em segundo plano, como por exemplo <i>(baixar conteúdo regularmente da rede)</i>.
 
  ### Ajustes no Projeto:
  - [x] Adicionado background mode capability:
    - Selecione o `project`
    - Abra `Target’s Capabilities`
    - Em `Background Mode` check `Background fetch`
  - [x] Abra o arquivo `AppDelegate.swift` e insira o método:<br>
  `func application(_ application: UIApplication, performFetchWithCompletionHandler completionHandler: @escaping (UIBackgroundFetchResult) -> Void) {} `
  - [x] Faça o aplicativo executar em segundo plano sem abrir ele:
    - Abra ` edit scheme`
    - Clique em `Run`
    - Check a opção `Background Fetch`
    
 ### Sample App Background Fetch
 - Exemplo gera de tempos em tempos, um número randomico em segundo plano, sem que o aplicativo esteja aberto.
  
 ## Print Screen :foggy:
 
| ![image01](imagens/fetch-ios-nativo.gif) |
|:---:|
| Background Fetch |

### Documentação de apoio
- Background Modes (Fetch)(https://medium.com/@vialyx/ios-dev-course-background-modes-fetch-70c18f9f58d5)


