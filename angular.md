<ion-header>
  <ion-toolbar>
    <ion-title>
      Lista de gêneros musicais
    </ion-title>
  </ion-toolbar>
</ion-header>

<ion-content class="ion-padding">

  <ion-list>
    <ion-item>
      <ion-input labelPlacement="floating" label="nome" [(ngModel)]="nome"></ion-input>
    </ion-item>
  </ion-list>

  <ion-item>
    <ion-button (click)="adicionar()"> Adicionar</ion-button>
  </ion-item>

  <ion-list>
    <ion-item *ngFor="let item of items; let posicao = index">
      <ion-label>
        {{item.titulo}}
      </ion-label>
      <ion-button slot="end" color="white" (click) = "remover(posicao)">
        <ion-icon slot="icon-only" name="trash-outline" color="danger"></ion-icon>
      </ion-button>
    </ion-item>
  </ion-list>
</ion-content>

Npm i
Import { FormsModule } from @angular/Forms
[(ngModel)]="Variável do ts"
Import { CommonsModule } from @angular/Commons
Npm i -g @angular/cli@14.2.13
