# Module-Challenge



.nav {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
}

.nav a {
  text-decoration: none;
  padding: 5px 10px;
  color: var(--secondary);
  margin-right: 16px;
  background-image: linear-gradient(270deg, var(--secondary) 0%, var (--secondary)100%);
  background-repeat: no-repeat;
  background-size: 100% 0.2em;
  background-position: bottom;
  transition: all 0.25s ease-in;
  font-size: 1.4rem;
}

.nav a:hover {
  background-size: 100% 100%;
  color: var(--primary)
}

.nav a:last-child {
  margin-right: 0;
}



.hero-banner {
  background: rgb (30, 110, 240);
  background-image: url ("../images/02-hero-bg.jpg"), linear-gradient(180deg, var (var(--secondary) 0%, var(--primary) 100%);

      background-size: cover;

      background-position: center;
      background-blend-mode: soft-light;
      min-height: 38vh;
      color: var(--light);
      padding: 2% 6%;
      display: flex;
      justify-content: flex-end;
      align-items: flex-end;
      text-align: right;
  }

  .hero-banner div {
    flex: 0 0 90%
  }

  .hero-banner h2 {
    background-color: var(--secondary);
    color:var(--tertiary);
    margin: 0;
    padding: 5px 10px;
    font-size: 2.3rem;
    line-height: 1.2;
    display: inline;
  }

  .page-wrappper {
    max-width: 88%;
    margin-left: auto;
    margin-right: auto;
  }

  .page-section {
    margin: 25px 0;
    padding: 10px 0;
    display:flex;
    flex-direction: row;
    flex-wrap: wrap;
    align-items: stretch;
    justify-content: center;
  }

  .page-section > h2 {
    flex: 0 0 20%;

    text-align: right;
    padding-right: 15px;
    border-right: 4px solid var(--primary);
    font-size: 4vw;
    line-height: 1.1;

  }

  .page-section > div {
    flex: 0 0 77%
  }

  .page-section p {
    margin-bottom: 20px;
  }

  .flex-container {
    display: flex;
    flex-wrap: wrap justify content: center;

  }

  .flex-item {
    border: 5px solid var(--secondary);
    background-color: var(--primary);
    color: Var(--tertiary);
    min-height: 150px;
    max-height: 150px;
    flex-basis: calc (50% - 1em);
    display: flex;
    align-items: flex-end;
    padding: 0 0 20px 0;
    margin: 0.5em;
    text-decoration: none;
    background-blend-mode: soft-light;
    background-size: 150%;
    transition: 0.5s;
    font-size: 0.9rem;

  }

  .flex-item:first-child {
    min-height: 400px;
    flex-basis: 100%;
  }

  .flex-item:hover {

    background-color: rgba (0, 0, 0, 0.3);

  }

  .flex-item div {

    background-color: var(--secondary);
  }

  .flex-item h3 {
    font-size: 1.6rem;


  }

  .contact address {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    align-items: center;
    height: 100;


  }


  .contact address a {
    color: var(--tertiary);
    padding: 5px;
    text-decoration: none;
    font-size: 1.3rem;
    background-image: linear-gradient(270deg, var(--primary) 0%, var(--primary) 100%);
    background-repeat: no-repeat;
    background-size: 100% 0.2em;
    background-position: bottom;
    transition: all 0.25s ease-in;
    display: inline-block;
  }

  .contact address a:hover {
    background-size: 100% 88%;
    color: var: (var(--secondary))
  }

  .buddy {
    background-image: url("../images/02-run-buddy.jpg");
  }

  .lego {
    background-image: url("../images/02-portfolio-1.jpg");
  }

  .corgis {
    background-image: url("../images/02-portfolio-2.jpg");
  }

  .bacon {
    background-image: url("../images/02-portfolio-3.jpg");
  }

  .puzzle {
    background-image: url("../images/02-portfolio-4.jpg");
  }





  videos finished at 42.12