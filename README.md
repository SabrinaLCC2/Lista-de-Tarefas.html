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

//////////////////////////////////////////////////////////////////////////////////////////////////
 /* Definindo uma cor de fundo para o corpo da página */
body {
    background-color: #f8f9fa; /* cor clara de fundo */
    font-family: Arial, sans-serif; /* alterando a fonte */
}

/* Estilo para o cabeçalho */
h1 {
    color: #007bff; /* cor azul */
    text-align: center; /* centralizando o texto */
}

/* Estilo para as tabelas */
table {
    width: 100%;
    border-collapse: collapse;
}

table th, table td {
    padding: 12px;
    border: 1px solid #ddd;
}

table th {
    background-color: #343a40;
    color: white;
}

table tr:nth-child(even) {
    background-color: #f2f2f2;
}

table tr:hover {
    background-color: #ddd;
}

/* Estilo para o botão de "Finalizar" */
button.finalizar-btn {
    background-color: #28a745;
    color: white;
    border: none;
    padding: 5px 10px;
    cursor: pointer;
    border-radius: 4px;
}

button.finalizar-btn:hover {
    background-color: #218838;
}



button.btn-edit { /* Botão Editar */
    background-color: #6c757d; /* cinza escuro */
    color: white;
    border: none;
}

button.btn-edit:hover {
    background-color: #5a6268; /* tom mais escuro de cinza */
}

button.btn-save { /* Botão Salvar */
    background-color: #6c757d; /* cinza escuro */
    color: white;
    border: none;
}

button.btn-save:hover {
    background-color: #5a6268; /* tom mais escuro de cinza */
}

button.btn-update { /* Botão Atualizar */
    background-color: #6c757d; /* cinza escuro */
    color: white;
    border: none;
}

button.btn-update:hover {
    background-color: #5a6268; /* tom mais escuro de cinza */
}
button.btn-add { /* Botão Adicionar */
    background-color: #6c757d; /* cinza escuro */
    color: white;
    border: none;
}

button.btn-add:hover {
    background-color: #5a6268; /* tom mais escuro de cinza */
}


/* Estilo para a div de botões dentro das células da tabela */
.btn-group {
    display: flex;
    justify-content: flex-end;
    gap: 5px; /* espaço entre os botões */
}

/* Melhorando a aparência dos tooltips */
.tooltip-inner {
    background-color: #343a40;
    color: white;
}

/* Adicionando sombra aos botões para destacar ao passar o mouse */
button:hover {
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
}

////////////////////////////////////////////////////////////////////////////////////////////


// Função para mudar o status da tarefa para "Finalizado"
function finalizarTarefa(id) {
  const row = document.getElementById('task-' + id); // seleciona a linha da tarefa
  const finalizarBtn = row.querySelector('.finalizar-btn'); // encontra o botão de finalizar

  // Verifica se o botão já foi clicado
  if (!finalizarBtn.classList.contains('completed')) {
      // Marca a tarefa como finalizada
      row.cells[4].innerText = 'Finalizado em ' + new Date().toLocaleDateString();
      finalizarBtn.classList.add('completed');
      finalizarBtn.innerText = 'Finalizada'; // Alterando o texto do botão
      finalizarBtn.disabled = true; // Desabilitando o botão após ser clicado
  }
}

// Espera o carregamento da página
document.addEventListener("DOMContentLoaded", () => {

// Evento para o botão "Escrever"
const writeButtons = document.querySelectorAll('.btn-warning');
writeButtons.forEach(button => {
  button.addEventListener('click', function () {
    const taskRow = this.closest('tr'); // Pega a linha da tarefa
    const taskTitle = taskRow.querySelector('td').textContent.trim(); // Pega o título da tarefa
    alert(`Você clicou para escrever sobre: ${taskTitle}`);
  });
});

// Evento para o botão "Salvar"
const saveButtons = document.querySelectorAll('.btn-success');
saveButtons.forEach(button => {
  button.addEventListener('click', function () {
    const taskRow = this.closest('tr');
    const taskTitle = taskRow.querySelector('td').textContent.trim();
    alert(`A tarefa "${taskTitle}" foi salva com sucesso.`);
  });
});

// Evento para o botão "Apagar"
const deleteButtons = document.querySelectorAll('.btn-danger');
deleteButtons.forEach(button => {
  button.addEventListener('click', function () {
    const taskRow = this.closest('tr');
    const taskTitle = taskRow.querySelector('td').textContent.trim();
    if (confirm(`Tem certeza que deseja apagar a tarefa "${taskTitle}"?`)) {
      taskRow.remove(); // Remove a linha da tabela
    }
  });
});

// Evento para o botão "Adicionar Data"
const addDateButtons = document.querySelectorAll('.btn-info');
addDateButtons.forEach(button => {
  button.addEventListener('click', function () {
    const taskRow = this.closest('tr');
    const taskTitle = taskRow.querySelector('td').textContent.trim();
    alert(`Adicionando uma nova data para a tarefa "${taskTitle}".`);
    // Aqui você pode adicionar lógica para permitir a seleção de uma data
  });
});

// Evento para o botão "Escrever" (edição de tarefa)
const editarButtons = document.querySelectorAll('.btn-warning');
editarButtons.forEach(button => {
  button.addEventListener('click', function() {
    const taskRow = this.closest('tr'); // Encontra a linha da tarefa
    const dataFinalizado = taskRow.querySelector('td').textContent; // Obtém a data de finalização
    // Aqui você pode adicionar um campo de edição, por exemplo:
    taskRow.querySelector('td').innerHTML = `<input type="date" value="${dataFinalizado}">`;
    // Altere o texto do botão para "Salvar"
    this.innerHTML = '<i class="fas fa-save"></i> Salvar';
    this.classList.replace('btn-warning', 'btn-success');
    // Mude a classe de "Salvar"
    this.addEventListener('click', salvarEdicao);
  });
});

// Evento para o botão "Salvar" (salvando edição de tarefa)
function salvarEdicao() {
  const taskRow = this.closest('tr');
  const input = taskRow.querySelector('input');
  const novaData = input.value;

  // Salvar a nova data no HTML
  taskRow.querySelector('td').textContent = novaData;

  // Alterar o botão de volta para "Escrever"
  this.innerHTML = '<i class="fas fa-edit"></i> Escrever';
  this.classList.replace('btn-success', 'btn-warning');

  // Remover o evento de salvar
  this.removeEventListener('click', salvarEdicao);
  this.addEventListener('click', editarButtons);
}

// Evento para o botão "Apagar"
const apagarButtons = document.querySelectorAll('.btn-danger');
apagarButtons.forEach(button => {
  button.addEventListener('click', function() {
    const taskRow = this.closest('tr');
    // Confirmar antes de apagar
    if (confirm('Tem certeza que deseja apagar esta tarefa?')) {
      taskRow.remove();
    }
  });
});

// Evento para o botão "Adicionar Data"
const adicionarDataButtons = document.querySelectorAll('.btn-info');
adicionarDataButtons.forEach(button => {
  button.addEventListener('click', function() {
    const taskRow = this.closest('tr');
    // Mostrar um prompt ou um modal para inserir a data
    const novaData = prompt('Digite a nova data de finalização (Formato: YYYY-MM-DD)');
    if (novaData) {
      taskRow.querySelector('td').textContent = novaData;
    }
  });
});

// Adiciona o ouvinte de evento de clique nos botões de "Finalizar"
const finalizarButtons = document.querySelectorAll('.finalizar-btn');
finalizarButtons.forEach(function(button) {
  button.addEventListener('click', function (event) {
    const taskId = event.target.closest('tr').dataset.id;
    finalizarTarefa(taskId); // chama a função para marcar a tarefa como finalizada
  });
});
});

