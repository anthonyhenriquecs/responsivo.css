# responsivo.css

@media (max-width: 1024px) {
  .cabecalho {
    justify-content: center;
    flex-direction: column;
    padding: 50px 0;
    gap: 15px;
  }

  .cabecalho .menu li a {
    padding: 15px;
  }

  .home .informacoes {
    padding: 30px;
  }

  .home .informacoes img {
    max-width: 100px;
  }

  .home .informacoes .titulo {
    font-size: 40px;
  }

  .compre-ja .cartao {
    width: 70%;
  }
}

@media (max-width: 768px) {
  .compre-ja {
    padding: 30px;
  }

  .compre-ja .cartao {
    padding: 80px 20px;
    width: 100%;
  }

  .compre-ja .informacoes h3 {
    font-size: 35px;
  }

  .compre-ja .informacoes .plataformas {
    flex-direction: column;
  }

  .btn-plataforma {
    margin-top: 15px;
    padding: 15px;
  }

  .btn-comprar {
    width: 100%;
  }
}

@media (max-width: 425px) {
  main::after {
    background: linear-gradient(90deg, rgba(0, 0, 0, 0.85), rgba(0, 0, 0, 0.4) 100%, transparent 65%);
  }

  .compre-ja .cartao .capa-do-jogo {
    max-width: 80%;
  }
}
