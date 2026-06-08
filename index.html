function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(220);
}
let terra;
let plantas = [];
let poluicao = [];
let barraSustentavel = 0;

function setup() {
  createCanvas(800, 500);
  terra = new Terra();
  
  // Criando plantas
  for (let i = 0; i < 5; i++) {
    plantas.push(new Planta(random(100, 700), height - 60));
  }
  
  // Criando poluição
  for (let i = 0; i < 5; i++) {
    poluicao.push(new Poluicao(random(100, 700), random(50, 200)));
  }
}

function draw() {
  background(135, 206, 235); // Céu azul inicial
  terra.show();
  
  // Mostrar plantas
  for (let planta of plantas) {
    planta.show();
  }
  
  // Mostrar poluição
  for (let p of poluicao) {
    p.show();
  }
  
  // Atualizar barra de sustentabilidade
  fill(34, 139, 34);
  rect(50, 30, barraSustentavel * 2, 20);
  noFill();
  stroke(0);
  rect(50, 30, 200, 20);
  noStroke();
  fill(0);
  textSize(14);
  text("Sustentabilidade", 50, 25);
}

function mousePressed() {
  // Regar plantas
  for (let planta of plantas) {
    if (dist(mouseX, mouseY, planta.x, planta.y) < 50) {
      planta.grow();
      barraSustentavel += 10;
      if (barraSustentavel > 200) barraSustentavel = 200;
    }
  }
  
  // Limpar poluição
  for (let i = poluicao.length - 1; i >= 0; i--) {
    if (dist(mouseX, mouseY, poluicao[i].x, poluicao[i].y) < 30) {
      poluicao.splice(i, 1);
      barraSustentavel += 15;
      if (barraSustentavel > 200) barraSustentavel = 200;
    }
  }
}

class Terra {
  constructor() {
    this.cor = color(139, 69, 19); // marrom seco
  }
  
  show() {
    fill(this.cor);
    rect(0, height - 50, width, 50);
  }
}

class Planta {
  constructor(x, y) {
    this.x = x;
    this.y = y;
    this.tamanho = 20;
  }
  
  grow() {
    this.tamanho += 10;
    if (this.tamanho > 80) this.tamanho = 80;
  }
  
  show() {
    fill(34, 139, 34);
    ellipse(this.x, this.y - this.tamanho / 2, 20, this.tamanho);
  }
}

class Poluicao {
  constructor(x, y) {
    this.x = x;
    this.y = y;
    this.tamanho = random(30, 50);
  }
  
  show() {
    fill(100);
    ellipse(this.x, this.y, this.tamanho);
  }
}
