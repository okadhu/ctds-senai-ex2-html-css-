Alunos: Kadhu, Weslley

# Orientações

## body
1. background-color: #f4f4f4;
2. color: #2c3e50;

## header
1. background-color: #2c3e50;

## .logo
1. color: #f1c40f;

## .menu li a
1. color: #f1c40f;

## .secao h1, secao h2
1. color: #2c3e50;

## .card
1. background-color: #fff;
2. border: 1px solid #ccc;
3. width: 220px;
4. box-shadow: 0 2px 5px rgba(0,0,0,0.1);

## .card button
1. border: none;
2. background-color: #f1c40f;
3. color: #2c3e50;
4. cursor: pointer;

## footer
1. background-color: #2c3e50;
2. color: white;

## footer a
1. color: #f1c40f;

## footer a:hover
1. text-decoration: underline;

## .depoimentos
1. background-color: #ffffff;

## .depoimento-lista
1. display: flex;
2. justify-content: center;
3. flex-wrap: wrap;

## .depoimento strong
1. color: #2c3e50;

## responsividade
@media (max-width: 768px) {
  .menu {
    flex-direction: column;
    align-items: flex-end;
    gap: 10px;
  }

  .produtos, .depoimento-lista {
    flex-direction: column;
    align-items: center;
  }

  footer {
    flex-direction: column;
    align-items: center;
  }
}
