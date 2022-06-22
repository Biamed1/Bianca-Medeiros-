import {Ponto} from './Ponto'
export class Quadrilatero{
    private pontoA: Ponto
    private pontoB: Ponto

    constructor(PontoA: Ponto, PontoB: Ponto){
        this.pontoA = PontoA
        this.pontoB = PontoB
    }

    pertencerArea(ponto: Ponto): boolean{
        if(this.pontoA.getX <= ponto.getX && ponto.getX <= this.pontoB.getX
             && this.pontoB.getY <= ponto.getY && ponto.getY <= this.pontoA.getY  ){
                 return true
             }else{
                 return false
             }
    }
}
