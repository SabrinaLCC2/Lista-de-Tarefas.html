<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>TWTodos - Lista de Tarefas</title>

  <!-- Favicon -->
  <link rel="icon" href="{% static 'favicon.ico' %}" type="image/x-icon">

  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">

  <!-- Font Awesome para os ícones -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">

  <!-- Vinculando o arquivo de CSS personalizado -->
  <link rel="stylesheet" href="assets/css/style.css">
</head>
<body>
  <nav class="navbar bg-dark mb-4" data-bs-theme="dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">TWTodos</a>
    </div>
  </nav>

  <main class="container">
    <h1>Lista de Tarefas</h1>

    <!-- Tabela de Tarefas -->
    <table class="table table-striped">
      <thead>
        <tr>
          <th scope="col">#</th>
          <th scope="col">Títulos</th>
          <th scope="col">Criado em</th>
          <th scope="col">Data de entrega</th>
          <th scope="col">Finalizado em</th>
        </tr>
      </thead>
      <tbody>
        <!-- Tarefa 1 -->
        <tr data-id="1" id="task-1">
          <th scope="row">1</th>
          <td>Revisar relatório
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-warning btn-sm" data-bs-toggle="tooltip" title="Editar título">
                <i class="fas fa-edit"></i> Editar
              </button>
              <button class="btn btn-success btn-sm" data-bs-toggle="tooltip" title="Salvar título">
                <i class="fas fa-save"></i> Salvar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar título">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
            </div>
          </td>
          <td>2024-12-01
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-info btn-sm" data-bs-toggle="tooltip" title="Atualizar data de criação">
                <i class="fas fa-calendar-alt"></i> Atualizar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar data de criação">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
            </div>
          </td>
          <td>2024-12-05
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-info btn-sm" data-bs-toggle="tooltip" title="Editar data de entrega">
                <i class="fas fa-calendar-day"></i> Editar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar data de entrega">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
            </div>
          </td>
          <td>2024-12-04
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-warning btn-sm" data-bs-toggle="tooltip" title="Escrever">
                <i class="fas fa-pencil-alt"></i> Escrever
              </button>
              <button class="btn btn-success btn-sm" data-bs-toggle="tooltip" title="Salvar">
                <i class="fas fa-save"></i> Salvar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
              <button class="btn btn-info btn-sm" data-bs-toggle="tooltip" title="Adicionar Data">
                <i class="fas fa-calendar-day"></i> Adicionar Data
              </button>
            </div>
          </td>
        </tr>

        <!-- Tarefa 2 -->
        <tr data-id="2" id="task-2">
          <th scope="row">2</th>
          <td>Revisar código
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-warning btn-sm" data-bs-toggle="tooltip" title="Editar título">
                <i class="fas fa-edit"></i> Editar
              </button>
              <button class="btn btn-success btn-sm" data-bs-toggle="tooltip" title="Salvar título">
                <i class="fas fa-save"></i> Salvar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar título">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
            </div>
          </td>
          <td>2024-12-02
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-info btn-sm" data-bs-toggle="tooltip" title="Atualizar data de criação">
                <i class="fas fa-calendar-alt"></i> Atualizar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar data de criação">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
            </div>
          </td>
          <td>2024-12-06
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-info btn-sm" data-bs-toggle="tooltip" title="Editar data de entrega">
                <i class="fas fa-calendar-day"></i> Editar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar data de entrega">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
            </div>
          </td>
          <td>2024-12-05
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-warning btn-sm" data-bs-toggle="tooltip" title="Escrever">
                <i class="fas fa-pencil-alt"></i> Escrever
              </button>
              <button class="btn btn-success btn-sm" data-bs-toggle="tooltip" title="Salvar">
                <i class="fas fa-save"></i> Salvar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
              <button class="btn btn-info btn-sm" data-bs-toggle="tooltip" title="Adicionar Data">
                <i class="fas fa-calendar-day"></i> Adicionar Data
              </button>
            </div>
          </td>
        </tr>

        <!-- Tarefa 3 -->
        <tr data-id="3" id="task-3">
          <th scope="row">3</th>
          <td>Realizar testes
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-warning btn-sm" data-bs-toggle="tooltip" title="Editar título">
                <i class="fas fa-edit"></i> Editar
              </button>
              <button class="btn btn-success btn-sm" data-bs-toggle="tooltip" title="Salvar título">
                <i class="fas fa-save"></i> Salvar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar título">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
            </div>
          </td>
          <td>2024-12-04
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-info btn-sm" data-bs-toggle="tooltip" title="Atualizar data de criação">
                <i class="fas fa-calendar-alt"></i> Atualizar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar data de criação">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
            </div>
          </td>
          <td>2024-12-08
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-info btn-sm" data-bs-toggle="tooltip" title="Editar data de entrega">
                <i class="fas fa-calendar-day"></i> Editar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar data de entrega">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
            </div>
          </td>
          <td>2024-12-07
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-warning btn-sm" data-bs-toggle="tooltip" title="Escrever">
                <i class="fas fa-pencil-alt"></i> Escrever
              </button>
              <button class="btn btn-success btn-sm" data-bs-toggle="tooltip" title="Salvar">
                <i class="fas fa-save"></i> Salvar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
              <button class="btn btn-info btn-sm" data-bs-toggle="tooltip" title="Adicionar Data">
                <i class="fas fa-calendar-day"></i> Adicionar Data
              </button>
            </div>
          </td>
        </tr>
       <!-- Tarefa 4 -->
        <tr data-id="4" id="task-4">
          <th scope="row">4</th>
          <td>Realizar testes
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-warning btn-sm" data-bs-toggle="tooltip" title="Editar título">
                <i class="fas fa-edit"></i> Editar
              </button>
              <button class="btn btn-success btn-sm" data-bs-toggle="tooltip" title="Salvar título">
                <i class="fas fa-save"></i> Salvar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar título">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
            </div>
          </td>
          <td>2024-12-04
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-info btn-sm" data-bs-toggle="tooltip" title="Atualizar data de criação">
                <i class="fas fa-calendar-alt"></i> Atualizar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar data de criação">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
            </div>
          </td>
          <td>2024-12-08
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-info btn-sm" data-bs-toggle="tooltip" title="Editar data de entrega">
                <i class="fas fa-calendar-day"></i> Editar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar data de entrega">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
            </div>
          </td>
          <td>2024-12-07
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-warning btn-sm" data-bs-toggle="tooltip" title="Escrever">
                <i class="fas fa-pencil-alt"></i> Escrever
              </button>
              <button class="btn btn-success btn-sm" data-bs-toggle="tooltip" title="Salvar">
                <i class="fas fa-save"></i> Salvar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
              <button class="btn btn-info btn-sm" data-bs-toggle="tooltip" title="Adicionar Data">
                <i class="fas fa-calendar-day"></i> Adicionar Data
              </button>
            </div>
          </td>
        </tr>

        <!-- Tarefa 5 -->
        <tr data-id="5" id="task-5">
          <th scope="row">5</th>
          <td>Realizar testes
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-warning btn-sm" data-bs-toggle="tooltip" title="Editar título">
                <i class="fas fa-edit"></i> Editar
              </button>
              <button class="btn btn-success btn-sm" data-bs-toggle="tooltip" title="Salvar título">
                <i class="fas fa-save"></i> Salvar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar título">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
            </div>
          </td>
          <td>2024-12-04
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-info btn-sm" data-bs-toggle="tooltip" title="Atualizar data de criação">
                <i class="fas fa-calendar-alt"></i> Atualizar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar data de criação">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
            </div>
          </td>
          <td>2024-12-08
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-info btn-sm" data-bs-toggle="tooltip" title="Editar data de entrega">
                <i class="fas fa-calendar-day"></i> Editar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar data de entrega">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
            </div>
          </td>
          <td>2024-12-07
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-warning btn-sm" data-bs-toggle="tooltip" title="Escrever">
                <i class="fas fa-pencil-alt"></i> Escrever
              </button>
              <button class="btn btn-success btn-sm" data-bs-toggle="tooltip" title="Salvar">
                <i class="fas fa-save"></i> Salvar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
              <button class="btn btn-info btn-sm" data-bs-toggle="tooltip" title="Adicionar Data">
                <i class="fas fa-calendar-day"></i> Adicionar Data
              </button>
            </div>
          </td>
        </tr>
        <!-- Tarefa 6 -->
        <tr data-id="6" id="task-6">
          <th scope="row">6</th>
          <td>Realizar testes
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-warning btn-sm" data-bs-toggle="tooltip" title="Editar título">
                <i class="fas fa-edit"></i> Editar
              </button>
              <button class="btn btn-success btn-sm" data-bs-toggle="tooltip" title="Salvar título">
                <i class="fas fa-save"></i> Salvar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar título">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
            </div>
          </td>
          <td>2024-12-04
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-info btn-sm" data-bs-toggle="tooltip" title="Atualizar data de criação">
                <i class="fas fa-calendar-alt"></i> Atualizar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar data de criação">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
            </div>
          </td>
          <td>2024-12-08
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-info btn-sm" data-bs-toggle="tooltip" title="Editar data de entrega">
                <i class="fas fa-calendar-day"></i> Editar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar data de entrega">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
            </div>
          </td>
          <td>2024-12-07
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-warning btn-sm" data-bs-toggle="tooltip" title="Escrever">
                <i class="fas fa-pencil-alt"></i> Escrever
              </button>
              <button class="btn btn-success btn-sm" data-bs-toggle="tooltip" title="Salvar">
                <i class="fas fa-save"></i> Salvar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
              <button class="btn btn-info btn-sm" data-bs-toggle="tooltip" title="Adicionar Data">
                <i class="fas fa-calendar-day"></i> Adicionar Data
              </button>
            </div>
          </td>
        </tr>

        <!-- Tarefa 7 -->
        <tr data-id="7" id="task-7">
          <th scope="row">7</th>
          <td>Realizar testes
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-warning btn-sm" data-bs-toggle="tooltip" title="Editar título">
                <i class="fas fa-edit"></i> Editar
              </button>
              <button class="btn btn-success btn-sm" data-bs-toggle="tooltip" title="Salvar título">
                <i class="fas fa-save"></i> Salvar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar título">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
            </div>
          </td>
          <td>2024-12-04
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-info btn-sm" data-bs-toggle="tooltip" title="Atualizar data de criação">
                <i class="fas fa-calendar-alt"></i> Atualizar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar data de criação">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
            </div>
          </td>
          <td>2024-12-08
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-info btn-sm" data-bs-toggle="tooltip" title="Editar data de entrega">
                <i class="fas fa-calendar-day"></i> Editar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar data de entrega">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
            </div>
          </td>
          <td>2024-12-07
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-warning btn-sm" data-bs-toggle="tooltip" title="Escrever">
                <i class="fas fa-pencil-alt"></i> Escrever
              </button>
              <button class="btn btn-success btn-sm" data-bs-toggle="tooltip" title="Salvar">
                <i class="fas fa-save"></i> Salvar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
              <button class="btn btn-info btn-sm" data-bs-toggle="tooltip" title="Adicionar Data">
                <i class="fas fa-calendar-day"></i> Adicionar Data
              </button>
            </div>
          </td>
        </tr>

        <!-- Tarefa 8 -->
        <tr data-id="8" id="task-8">
          <th scope="row">8</th>
          <td>Realizar testes
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-warning btn-sm" data-bs-toggle="tooltip" title="Editar título">
                <i class="fas fa-edit"></i> Editar
              </button>
              <button class="btn btn-success btn-sm" data-bs-toggle="tooltip" title="Salvar título">
                <i class="fas fa-save"></i> Salvar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar título">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
            </div>
          </td>
          <td>2024-12-04
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-info btn-sm" data-bs-toggle="tooltip" title="Atualizar data de criação">
                <i class="fas fa-calendar-alt"></i> Atualizar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar data de criação">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
            </div>
          </td>
          <td>2024-12-08
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-info btn-sm" data-bs-toggle="tooltip" title="Editar data de entrega">
                <i class="fas fa-calendar-day"></i> Editar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar data de entrega">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
            </div>
          </td>
          <td>2024-12-07
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-warning btn-sm" data-bs-toggle="tooltip" title="Escrever">
                <i class="fas fa-pencil-alt"></i> Escrever
              </button>
              <button class="btn btn-success btn-sm" data-bs-toggle="tooltip" title="Salvar">
                <i class="fas fa-save"></i> Salvar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
              <button class="btn btn-info btn-sm" data-bs-toggle="tooltip" title="Adicionar Data">
                <i class="fas fa-calendar-day"></i> Adicionar Data
              </button>
            </div>
          </td>
        </tr>

        <!-- Tarefa 9 -->
        <tr data-id="9" id="task-9">
          <th scope="row">9</th>
          <td>Realizar testes
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-warning btn-sm" data-bs-toggle="tooltip" title="Editar título">
                <i class="fas fa-edit"></i> Editar
              </button>
              <button class="btn btn-success btn-sm" data-bs-toggle="tooltip" title="Salvar título">
                <i class="fas fa-save"></i> Salvar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar título">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
            </div>
          </td>
          <td>2024-12-04
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-info btn-sm" data-bs-toggle="tooltip" title="Atualizar data de criação">
                <i class="fas fa-calendar-alt"></i> Atualizar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar data de criação">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
            </div>
          </td>
          <td>2024-12-08
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-info btn-sm" data-bs-toggle="tooltip" title="Editar data de entrega">
                <i class="fas fa-calendar-day"></i> Editar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar data de entrega">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
            </div>
          </td>
          <td>2024-12-07
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-warning btn-sm" data-bs-toggle="tooltip" title="Escrever">
                <i class="fas fa-pencil-alt"></i> Escrever
              </button>
              <button class="btn btn-success btn-sm" data-bs-toggle="tooltip" title="Salvar">
                <i class="fas fa-save"></i> Salvar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
              <button class="btn btn-info btn-sm" data-bs-toggle="tooltip" title="Adicionar Data">
                <i class="fas fa-calendar-day"></i> Adicionar Data
              </button>
            </div>
          </td>
        </tr>

        <!-- Tarefa 10 -->
        <tr data-id="10" id="task-10">
          <th scope="row">10</th>
          <td>Realizar testes
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-warning btn-sm" data-bs-toggle="tooltip" title="Editar título">
                <i class="fas fa-edit"></i> Editar
              </button>
              <button class="btn btn-success btn-sm" data-bs-toggle="tooltip" title="Salvar título">
                <i class="fas fa-save"></i> Salvar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar título">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
            </div>
          </td>
          <td>2024-12-04
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-info btn-sm" data-bs-toggle="tooltip" title="Atualizar data de criação">
                <i class="fas fa-calendar-alt"></i> Atualizar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar data de criação">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
            </div>
          </td>
          <td>2024-12-08
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-info btn-sm" data-bs-toggle="tooltip" title="Editar data de entrega">
                <i class="fas fa-calendar-day"></i> Editar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar data de entrega">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
            </div>
          </td>
          <td>2024-12-07
            <div class="btn-group mt-2 text-end">
              <button class="btn btn-warning btn-sm" data-bs-toggle="tooltip" title="Escrever">
                <i class="fas fa-pencil-alt"></i> Escrever
              </button>
              <button class="btn btn-success btn-sm" data-bs-toggle="tooltip" title="Salvar">
                <i class="fas fa-save"></i> Salvar
              </button>
              <button class="btn btn-danger btn-sm" data-bs-toggle="tooltip" title="Apagar">
                <i class="fas fa-trash-alt"></i> Apagar
              </button>
              <button class="btn btn-info btn-sm" data-bs-toggle="tooltip" title="Adicionar Data">
                <i class="fas fa-calendar-day"></i> Adicionar Data
              </button>
            </div>
          </td>
        </tr>
        <!-- Repita o mesmo formato para as tarefas 5, 6 e 7 -->
        
      </tbody>
    </table>  
  </main>

   <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>

  <!-- Vinculando o arquivo JavaScript personalizado -->
  <script src="towtds.js"></script>

  <script>
    // Inicializar tooltips do Bootstrap
    document.addEventListener("DOMContentLoaded", () => {
      const tooltipTriggerList = document.querySelectorAll('[data-bs-toggle="tooltip"]');
      tooltipTriggerList.forEach(tooltipTriggerEl => new bootstrap.Tooltip(tooltipTriggerEl));
    });
  </script>
</body>
</html>




   

   
   
    





   
  

  
