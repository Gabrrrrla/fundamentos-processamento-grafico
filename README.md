Processamento Gráfico 2025/2
Este repositório contém exemplos e códigos utilizados na disciplina de Processamento Gráfico: Fundamentos do curso Ciência da Computação da Unisinos. Ele é estruturado para facilitar a organização dos arquivos e a compilação dos projetos utilizando CMake.

📂 Estrutura do Repositório
📂 FCG2025-1/
├── 📂 include/               # Cabeçalhos e bibliotecas de terceiros
│   ├── 📂 glad/              # Cabeçalhos da GLAD (OpenGL Loader)
│   │   ├── glad.h
│   │   ├── 📂 KHR/           # Diretório com cabeçalhos da Khronos (GLAD)
│   │       ├── khrplatform.h
├── 📂 common/                # Código reutilizável entre os projetos
│   ├── glad.c                 # Implementação da GLAD
├── 📂 src/                    # Código-fonte dos exemplos e exemplos/
│   ├── HelloTriangle.cpp      # Exemplo básico de renderização com OpenGL
│   ├── ...                    # Outros exemplos e exercícios futuros
├── 📂 build/                  # Diretório gerado pelo CMake (não incluído no repositório)
├── 📄 CMakeLists.txt          # Configuração do CMake para compilar os projetos
├── 📄 README.md               # Este arquivo, com a documentação do repositório
├── 📄 GettingStarted.md       # Tutorial detalhado sobre como compilar usando o CMake
├── 📄 ...  
