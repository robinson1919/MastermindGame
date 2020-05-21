<template>
  <div id="app">
    <div class="container" fluid="md">
      <h1 class="text-center">Mastermind</h1>
      <div class="col-md-2 ml-5">
        <input type="text" class="col-md-1 hv" ref="special27" @click="selected(33)" v-b-modal.modal-1>      
        <input type="text" class="col-md-1 hv" ref="special28" @click="selected(34)" v-b-modal.modal-1> 
        <input type="text" class="col-md-1 hv" ref="special29" @click="selected(35)" v-b-modal.modal-1> 
        <input type="text" class="col-md-1 hv" ref="special30" @click="selected(36)" v-b-modal.modal-1> 
      </div>
      <b-row >
        <b-card
          title="Game"
          style="max-width: 1000rem;"
          class="mx-auto"
        >
          <b-row class="col-md-12">
            <!-- :class="[class1]" -->
            
            <input type="text" class="col-md-2 1" ref="selec1"  @click="selected(1)" v-b-modal.modal-1>
            <input type="text" class="col-md-2 2" ref="selec2" @click="selected(2)" v-b-modal.modal-1>
            <input type="text" class="col-md-2 3" ref="selec3" @click="selected(3)" v-b-modal.modal-1>
            <input type="text" class="col-md-2 4" ref="selec4" @click="selected(4)" v-b-modal.modal-1>  
            &nbsp;&nbsp;
            <div class="col-md-2 ml-5">
              <input type="text" ref="l1" class="col-md-1">      
              <input type="text" ref="l2" class="col-md-1"> 
              <input type="text" ref="l3" class="col-md-1"> 
              <input type="text" ref="l4" class="col-md-1"> 
            </div>
            <button class="btn btn-primary" @click="test1">Set</button> 
          </b-row>

          <br><br>
          <b-row class="col-md-12">
            <input type="text" class="col-md-2" ref="selec5" v-b-modal.modal-1 @click="selected(5)">
            <input type="text" class="col-md-2" ref="selec6" v-b-modal.modal-1 @click="selected(6)">
            <input type="text" class="col-md-2" ref="selec7" v-b-modal.modal-1 @click="selected(7)">
            <input type="text" class="col-md-2" ref="selec8" v-b-modal.modal-1 @click="selected(8)"> 
            &nbsp;&nbsp;
            <div class="col-md-2 ml-5">
              <input type="text" ref="l5" class="col-md-1 5">      
              <input type="text" ref="l6" class="col-md-1 6"> 
              <input type="text" ref="l7" class="col-md-1 7"> 
              <input type="text" ref="l8" class="col-md-1 8"> 
            </div>       
              <button class="btn btn-primary" @click="test2">Set</button> 
          </b-row>
          
          <br><br>
          <b-row class="col-md-12">
            <input type="text" class="col-md-2" ref="selec9" v-b-modal.modal-1 @click="selected(9)">
            <input type="text" class="col-md-2" ref="selec10" v-b-modal.modal-1 @click="selected(10)">
            <input type="text" class="col-md-2" ref="selec11" v-b-modal.modal-1 @click="selected(11)">
            <input type="text" class="col-md-2" ref="selec12" v-b-modal.modal-1 @click="selected(12)">  
            &nbsp;&nbsp;
            <div class="col-md-2 ml-5">
              <input type="text" ref="l9" class="col-md-1">      
              <input type="text" ref="l10" class="col-md-1"> 
              <input type="text" ref="l11" class="col-md-1"> 
              <input type="text" ref="l12" class="col-md-1"> 
            </div>  
            <button class="btn btn-primary" @click="test3">Set</button>          
          </b-row>
          
          <br><br>
          <b-row class="col-md-12">
            <input type="text" class="col-md-2" ref="selec13" v-b-modal.modal-1 @click="selected(13)">
            <input type="text" class="col-md-2" ref="selec14" v-b-modal.modal-1 @click="selected(14)">
            <input type="text" class="col-md-2" ref="selec15" v-b-modal.modal-1 @click="selected(15)">
            <input type="text" class="col-md-2" ref="selec16" v-b-modal.modal-1 @click="selected(16)">    
            &nbsp;&nbsp;
            <div class="col-md-2 ml-5">
              <input type="text" ref="l13" class="col-md-1">      
              <input type="text" ref="l14" class="col-md-1"> 
              <input type="text" ref="l15" class="col-md-1"> 
              <input type="text" ref="l16" class="col-md-1"> 
            </div>  
            <button class="btn btn-primary" @click="test4">Set</button>        
          </b-row>

          <br><br>
          <b-row class="col-md-12">
            <input type="text" class="col-md-2" ref="selec17" v-b-modal.modal-1 @click="selected(17)">
            <input type="text" class="col-md-2" ref="selec18" v-b-modal.modal-1 @click="selected(18)">
            <input type="text" class="col-md-2" ref="selec19" v-b-modal.modal-1 @click="selected(19)">
            <input type="text" class="col-md-2" ref="selec20" v-b-modal.modal-1 @click="selected(20)">   
            &nbsp;&nbsp;
            <div class="col-md-2 ml-5">
              <input type="text" ref="l17" class="col-md-1">      
              <input type="text" ref="l18" class="col-md-1"> 
              <input type="text" ref="l19" class="col-md-1"> 
              <input type="text" ref="l20" class="col-md-1"> 
            </div>   
            <button class="btn btn-primary" @click="test5">Set</button>        
          </b-row>

          <br><br>
          <b-row class="col-md-12">
            <input type="text" class="col-md-2" ref="selec21" v-b-modal.modal-1 @click="selected(21)">
            <input type="text" class="col-md-2" ref="selec22" v-b-modal.modal-1 @click="selected(22)">
            <input type="text" class="col-md-2" ref="selec23" v-b-modal.modal-1 @click="selected(23)">
            <input type="text" class="col-md-2" ref="selec24" v-b-modal.modal-1 @click="selected(24)">
            &nbsp;&nbsp;
            <div class="col-md-2 ml-5">
              <input type="text" ref="l21" class="col-md-1">      
              <input type="text" ref="l22" class="col-md-1"> 
              <input type="text" ref="l23" class="col-md-1"> 
              <input type="text" ref="l24" class="col-md-1"> 
            </div>   
            <button class="btn btn-primary" @click="test6">Set</button>            
          </b-row>

          <br><br>
          <b-row class="col-md-12">
            <input type="text" class="col-md-2" ref="selec25" v-b-modal.modal-1 @click="selected(25)">
            <input type="text" class="col-md-2" ref="selec26" v-b-modal.modal-1 @click="selected(26)">
            <input type="text" class="col-md-2" ref="selec27" v-b-modal.modal-1 @click="selected(27)">
            <input type="text" class="col-md-2" ref="selec28" v-b-modal.modal-1 @click="selected(28)"> 

            <div class="col-md-2 ml-5">
              <input type="text" ref="l25" class="col-md-1">      
              <input type="text" ref="l26" class="col-md-1"> 
              <input type="text" ref="l27" class="col-md-1"> 
              <input type="text" ref="l28" class="col-md-1"> 
            </div> 
            <button class="btn btn-primary" @click="test7">Set</button>        
          </b-row>

          <br><br>
          <b-row class="col-md-12">
            <input type="text" class="col-md-2" ref="selec29" v-b-modal.modal-1 @click="selected(29)">
            <input type="text" class="col-md-2" ref="selec30" v-b-modal.modal-1 @click="selected(30)">
            <input type="text" class="col-md-2" ref="selec31" v-b-modal.modal-1 @click="selected(31)">
            <input type="text" class="col-md-2" ref="selec32" v-b-modal.modal-1 @click="selected(32)">    
            &nbsp;&nbsp;
            <div class="col-md-2 ml-5">
              <input type="text" ref="l29" class="col-md-1">      
              <input type="text" ref="l30" class="col-md-1"> 
              <input type="text" ref="l31" class="col-md-1"> 
              <input type="text" ref="l32" class="col-md-1"> 
            </div>      
            <button class="btn btn-primary" @click="test8">Set</button>      
          </b-row>
          
        </b-card>
      </b-row>

      <b-modal id="modal-1" title="Pick a color">
        <b-row class="col-md-12 mx-auto" >
          <input type="text" class="col-md-2 blue hv" v-model="blue" @click="getColor(1)">
          <input type="text" class="col-md-2 red hv" v-model="red" @click="getColor(2)">
          <input type="text" class="col-md-2 yellow hv" v-model="yellow" @click="getColor(3)">
        </b-row>
        <b-row class="col-md-12 mx-auto">
          <input type="text" class="col-md-2 green hv" v-model="green" @click="getColor(4)">
          <input type="text" class="col-md-2 white hv" v-model="white" @click="getColor(5)">
          <input type="text" class="col-md-2 black hv" v-model="black" @click="getColor(6)">
        </b-row>
      </b-modal>

      <b-modal ref="winMod" id="modal-2" v-model="modalWIn" class="text-center" title="Congratulations">
        <h3>You have already won the game</h3>
      </b-modal>

      
      
    </div>
  </div>
</template>

<script>
export default {
  data: () => ({
    selec1: '',
    selec2: '',
    selec3: '',
    selec4: '',
    selec5: '',
    selec6: '',
    selec7: '',
    selec8: '',
    selec9: '',
    selec10: '',
    selec11: '',
    selec12: '',
    selec13: '',
    selec14: '',
    selec15: '',
    selec16: '',
    selec17: '',
    selec18: '',
    selec19: '',
    selec20: '',
    selec21: '',
    selec22: '',
    selec23: '',
    selec24: '',
    selec25: '',
    selec27: '',
    selec28: '',
    selec29: '',
    selec30: '',
    selec31: '',
    selec32: '',
    special27: '',
    special28: '',
    special29: '',
    special30: '',
    blue: '',
    red: '',
    yellow: '',
    green: '',
    black: '',
    white: '',
    val: '',    
    selClass: '',
    valC: '',
    opt: [],
    validationArr: [],
    selection: '',
    otr: '',
    modalWIn: false,
  }),

  created(){

  },
  computed:{
    
  },
  methods:{
    reset(){
      this.valC = '';
      this.selec1 = '';
      this.selec2 = '';
      this.selec3 = '';
      this.selec4 = '';
      this.selec5 = '';
      this.selec6 = '';
      this.selec7 = '';
      this.selec8 = '';
      this.selec9 = '';
      this.selec10 = '';
      this.selec11 = '';
      this.selec12 = '';
      this.selec13 = '';
      this.selec14 = '';
      this.selec15 = '';
      this.selec16 = '';
      this.selec17 = '';
      this.selec18 = '';
      this.selec19 = '';
      this.selec20 = '';
      this.selec21 = '';
      this.selec22 = '';
      this.selec23 = '';
      this.selec24 = '';
      this.selec25 = '';
      this.selec27 = '';
      this.selec28 = '';
      this.selec29 = '';
      this.selec30 = '';
      this.selec31 = '';
      this.selec32 = '';
      this.special27 = '';
      this.special28 = '';
      this.special29 = '';
      this.special30 = '';
      this.otr = '';
      this.opt = [];
      this.validationArr = [];
    },

    selected(val){
      this.valC = '';
      this.otr = '';

      this.otr = val;
      
      switch (val) {
        case 1:
          this.valC = this.$refs.selec1;
          break;
        
        case 2:
          this.valC = this.$refs.selec2;
          break

        case 3:
          this.valC = this.$refs.selec3;
          break;

        case 4:
          this.valC = this.$refs.selec4;
          break;

        case 5:
          this.valC = this.$refs.selec5;
          break;
        
        case 6:
          this.valC = this.$refs.selec6;
          break;

        case 7:
          this.valC = this.$refs.selec7;
          break;

        case 8:
          this.valC = this.$refs.selec8;
          break;

        case 9:
          this.valC = this.$refs.selec9;
          break;

        case 10:
          this.valC = this.$refs.selec10;
          break;

        case 11:
          this.valC = this.$refs.selec11;
          break;

        case 12:
          this.valC = this.$refs.selec12;
          break;

        case 13:
          this.valC = this.$refs.selec13;
          break;

        case 14:
          this.valC = this.$refs.selec14;
          break;

        case 15:
          this.valC = this.$refs.selec15;
          break;

        case 16:
          this.valC = this.$refs.selec16;
          break;

        case 17:
          this.valC = this.$refs.selec17;
          break;

        case 18:
          this.valC = this.$refs.selec18;
          break;

        case 19:
          this.valC = this.$refs.selec19;
          break;

        case 20:
          this.valC = this.$refs.selec20;
          break;

        case 21:
          this.valC = this.$refs.selec21;
          break;

        case 22:
          this.valC = this.$refs.selec22;
          break;

        case 23:
          this.valC = this.$refs.selec23;
          break;

        case 24:
          this.valC = this.$refs.selec24;
          break;

        case 25:
          this.valC = this.$refs.selec25;
          break;

        case 26:
          this.valC = this.$refs.selec26;
          break;

        case 27:
          this.valC = this.$refs.selec27;
          break;

        case 28:
          this.valC = this.$refs.selec28;
          break;

        case 29:
          this.valC = this.$refs.selec29;
          break;

        case 30:
          this.valC = this.$refs.selec30;
          break;

        case 31:
          this.valC = this.$refs.selec31;
          break;
          
        case 32:
          this.valC = this.$refs.selec32;
          break;

        case 33:
          this.valC = this.$refs.special27;
          break;

        case 34:
          this.valC = this.$refs.special28;
          break;

        case 35:
          this.valC = this.$refs.special29;
          break;

        case 36:
          this.valC = this.$refs.special30;
          break;
          

        default:
          this.selClass = 'brown';
          break; 

      }
    },
    
    getColor(color){
      switch (color) {
        case 1:
          this.valC.classList.add("blue");
          // -------------------
          
          break;
        
        case 2:
          this.valC.classList.add("red");
          
          break

        case 3:
          this.valC.classList.add("yellow");
          
          break;

        case 4:
          this.valC.classList.add("green");
          break;

        case 5:
          this.valC.classList.add("white");
          break;
        
        case 6:
          this.valC.classList.add("black");
          break;

        default:
          this.selClass = 'brown';
          break;
      }

    
      switch (this.otr) {
        case 1:
          this.selec1 = color;
          break;
        
        case 2:
          this.selec2 = color;
          break

        case 3:
          this.selec3 = color;
          break;

        case 4:
          this.selec4 = color;
          break;

        case 5:
          this.selec5 = color;
          break;
        
        case 6:
          this.selec6 = color;
          break;

        case 7:
          this.selec7 = color;
          break;

        case 8:
          this.selec8 = color;
          break;

        case 9:
          this.selec9 = color;
          break;

        case 10:
          this.selec10 = color;
          break;

        case 11:
          this.selec11 = color;
          break;

        case 12:
          this.selec12 = color;
          break;

        case 13:
          this.selec13 = color;
          break;

        case 14:
          this.selec14 = color;
          break;

        case 15:
          this.selec15 = color;
          break;

        case 16:
          this.selec16 = color;
          break;

        case 17:
          this.selec17 = color;
          break;

        case 18:
          this.selec18 = color;
          break;

        case 19:
          this.selec19 = color;
          break;

        case 20:
          this.selec20 = color;
          break;

        case 21:
          this.selec21 = color;
          break;

        case 22:
          this.selec22 = color;
          break;

        case 23:
          this.selec23 = color;
          break;

        case 24:
          this.selec24 = color;
          break;

        case 25:
          this.selec25 = color;
          break;

        case 26:
          this.selec26 = color;
          break;

        case 27:
          this.selec27 = color;
          break;

        case 28:
          this.selec28 = color;
          break;

        case 29:
          this.selec29 = color;
          break;

        case 30:
          this.selec30 = color;
          break;

        case 31:
          this.selec31 = color;
          break;
        
        case 32:
          this.selec32 = color;
          break;

        case 33:
          this.special27 = color;
          break;

        case 34:
          this.special28 = color;
          break;

        case 35:
          this.special29 = color;
          break;

        case 36:
          this.special30 = color;
          break;

        default:
          this.selClass = 'brown';
          break; 

      }
    }, 
    
    test1(){
      if(this.opt.length < 4) {
          if(this.special27 && this.special28 && this.special29 && this.special30){
          this.opt.push(this.special27, this.special28, this.special29, this.special30);
        }
      }
      // --------------------------------------------------------------

      if(this.selec1 && this.selec2 && this.selec3 && this.selec4){
        this.validationArr = [];
        if(this.validationArr.length < 4) {
          this.validationArr.push(this.selec1, this.selec2, this.selec3, this.selec4)
        }   
        // --------------------------------------------------------------
      
        
        
        var arr = [];
        this.validationArr.forEach((x)=>{          
          this.opt.forEach((el) => {
            if (x == el){

              
              arr.push(x);

              switch (arr.length){
                case 1:
                  this.$refs.l1.classList.add("yellow");
                  break;

                case 2:
                  this.$refs.l1.classList.add("yellow");
                  this.$refs.l2.classList.add("yellow");
                  break;

                case 3:
                  this.$refs.l1.classList.add("yellow");
                  this.$refs.l2.classList.add("yellow");
                  this.$refs.l3.classList.add("yellow");
                  break;
                
                case 4:
                  this.$refs.l1.classList.add("yellow");
                  this.$refs.l2.classList.add("yellow");
                  this.$refs.l3.classList.add("yellow");
                  this.$refs.l4.classList.add("yellow");
                  break;

              }

              //  Codigo anterior con colores ordenados por posicion
        
              // var index = '';
              // var index = this.validationArr.indexOf(x);

              // if(index == 0){
              //   this.$refs.l1.classList.add("yellow");
              // }
                  
              // if (index == 1){
              //   this.$refs.l2.classList.add("yellow");
              // }
                
              // if(index == 2) {
              //   this.$refs.l3.classList.add("yellow");
              // }

              // if(index == 3) {
              //   this.$refs.l4.classList.add("yellow");
              // }

            }
          })
        })

        

        var newArr = [];
        for (let i = 0; i < this.validationArr.length; i++) {
          if(this.validationArr[i] == this.opt[i]){
            newArr.push(this.validationArr[i])
            
            
            switch (newArr.length){
              case 1:
                this.$refs.l1.classList.add("black");
                break;

              case 2:
                this.$refs.l1.classList.add("black");
                this.$refs.l2.classList.add("black");
                break;

              case 3:
                this.$refs.l1.classList.add("black");
                this.$refs.l2.classList.add("black");
                this.$refs.l3.classList.add("black");
                break;
              
              case 4:
                this.$refs.l1.classList.add("black");
                this.$refs.l2.classList.add("black");
                this.$refs.l3.classList.add("black");
                this.$refs.l4.classList.add("black");
                break;

              }
          }     
          
        }

        // Previous code with color ordered by columns


        // if (this.validationArr[0] == this.opt[0]){
        //   this.$refs.l1.classList.add("black");
        // }

        // if (this.validationArr[1] == this.opt[1]){
        //   this.$refs.l2.classList.add("black");
        // }

        // if (this.validationArr[2] == this.opt[2]){
        //   this.$refs.l3.classList.add("black");
        // }

        // if (this.validationArr[3] == this.opt[3]){
        //   this.$refs.l4.classList.add("black");
        // }

        // check if player won 

        if(this.validationArr[0] == this.opt[0] && this.validationArr[1] == this.opt[1] && this.validationArr[2] == this.opt[2] && this.validationArr[3] == this.opt[3]){
          this.modalWIn = true;
        }

        this.validationArr = [];
      }
      // -----------------------------------------------------------------
    },

    test2(){
      if(this.opt.length < 4) {
          if(this.special27 && this.special28 && this.special29 && this.special30){
          this.opt.push(this.special27, this.special28, this.special29, this.special30);
        }
      }

      // --------------------------------------------------------------
      if(this.selec5 && this.selec6 && this.selec7 && this.selec8){
        if(this.validationArr.length < 4) {
          this.validationArr = [];
          this.validationArr.push(this.selec5, this.selec6, this.selec7, this.selec8)
        }   
        // --------------------------------------------------------------
      
      
        var arr = [];
        this.validationArr.forEach((x)=>{          
          this.opt.forEach((el) => {
            if (x == el){              
              arr.push(x);

              switch (arr.length){
                case 1:
                  this.$refs.l5.classList.add("yellow");
                  break;

                case 2:
                  this.$refs.l5.classList.add("yellow");
                  this.$refs.l6.classList.add("yellow");
                  break;

                case 3:
                  this.$refs.l5.classList.add("yellow");
                  this.$refs.l6.classList.add("yellow");
                  this.$refs.l7.classList.add("yellow");
                  break;
                
                case 4:
                  this.$refs.l5.classList.add("yellow");
                  this.$refs.l6.classList.add("yellow");
                  this.$refs.l7.classList.add("yellow");
                  this.$refs.l8.classList.add("yellow");
                  break;

              }
            }
          })
        })

        

        var newArr = [];
        for (let i = 0; i < this.validationArr.length; i++) {
          if(this.validationArr[i] == this.opt[i]){
            newArr.push(this.validationArr[i])
            
            
            switch (newArr.length){
              case 1:
                this.$refs.l5.classList.add("black");
                break;

              case 2:
                this.$refs.l5.classList.add("black");
                this.$refs.l6.classList.add("black");
                break;

              case 3:
                this.$refs.l5.classList.add("black");
                this.$refs.l6.classList.add("black");
                this.$refs.l7.classList.add("black");
                break;
              
              case 4:
                this.$refs.l5.classList.add("black");
                this.$refs.l6.classList.add("black");
                this.$refs.l7.classList.add("black");
                this.$refs.l8.classList.add("black");
                break;

              }
          }     
          
        }

        // check if player won 

        if(this.validationArr[0] == this.opt[0] && this.validationArr[1] == this.opt[1] && this.validationArr[2] == this.opt[2] && this.validationArr[3] == this.opt[3]){
          this.modalWIn = true;
        }

        this.validationArr = [];
      }
      // -----------------------------------------------------
    },

    test3(){
      if(this.opt.length < 4) {
          if(this.special27 && this.special28 && this.special29 && this.special30){
          this.opt.push(this.special27, this.special28, this.special29, this.special30);
        }
      }

      // --------------------------------------------------------------
      if(this.selec9 && this.selec10 && this.selec11 && this.selec12){
        if(this.validationArr.length < 4) {
          this.validationArr.push(this.selec9, this.selec10, this.selec11, this.selec12)
        }   
        // --------------------------------------------------------------
      
      
        var arr = [];
        this.validationArr.forEach((x)=>{          
          this.opt.forEach((el) => {
            if (x == el){              
              arr.push(x);

              switch (arr.length){
                case 1:
                  this.$refs.l9.classList.add("yellow");
                  break;

                case 2:
                  this.$refs.l9.classList.add("yellow");
                  this.$refs.l10.classList.add("yellow");
                  break;

                case 3:
                  this.$refs.l9.classList.add("yellow");
                  this.$refs.l10.classList.add("yellow");
                  this.$refs.l11.classList.add("yellow");
                  break;
                
                case 4:
                  this.$refs.l9.classList.add("yellow");
                  this.$refs.l10.classList.add("yellow");
                  this.$refs.l11.classList.add("yellow");
                  this.$refs.l12.classList.add("yellow");
                  break;

              }
            }
          })
        })

        

        var newArr = [];
        for (let i = 0; i < this.validationArr.length; i++) {
          if(this.validationArr[i] == this.opt[i]){
            newArr.push(this.validationArr[i])
            
            
            switch (newArr.length){
              case 1:
                this.$refs.l9.classList.add("black");
                break;

              case 2:
                this.$refs.l9.classList.add("black");
                this.$refs.l10.classList.add("black");
                break;

              case 3:
                this.$refs.l9.classList.add("black");
                this.$refs.l10.classList.add("black");
                this.$refs.l11.classList.add("black");
                break;
              
              case 4:
                this.$refs.l9.classList.add("black");
                this.$refs.l10.classList.add("black");
                this.$refs.l11.classList.add("black");
                this.$refs.l12.classList.add("black");
                break;

              }
          }     
          
        }

        // check if player won 

        if(this.validationArr[0] == this.opt[0] && this.validationArr[1] == this.opt[1] && this.validationArr[2] == this.opt[2] && this.validationArr[3] == this.opt[3]){
          this.modalWIn = true;
        }

        this.validationArr = [];
      }
      // -----------------------------------------------------

      

    },

    test4(){
      // coder player set initial values for the game
      if(this.opt.length < 4) {
          if(this.special27 && this.special28 && this.special29 && this.special30){
          this.opt.push(this.special27, this.special28, this.special29, this.special30);
        }
      }
      
      // --------------------------------------------------------------
      if(this.selec13 && this.selec14 && this.selec15 && this.selec16){
        if(this.validationArr.length < 4) {
          this.validationArr.push(this.selec13, this.selec14, this.selec15, this.selec16)
        }   
        // --------------------------------------------------------------
      
      
        var arr = [];
        this.validationArr.forEach((x)=>{          
          this.opt.forEach((el) => {
            if (x == el){              
              arr.push(x);

              switch (arr.length){
                case 1:
                  this.$refs.l13.classList.add("yellow");
                  break;

                case 2:
                  this.$refs.l13.classList.add("yellow");
                  this.$refs.l14.classList.add("yellow");
                  break;

                case 3:
                  this.$refs.l13.classList.add("yellow");
                  this.$refs.l14.classList.add("yellow");
                  this.$refs.l15.classList.add("yellow");
                  break;
                
                case 4:
                  this.$refs.l13.classList.add("yellow");
                  this.$refs.l14.classList.add("yellow");
                  this.$refs.l15.classList.add("yellow");
                  this.$refs.l16.classList.add("yellow");
                  break;

              }
            }
          })
        })

        

        var newArr = [];
        for (let i = 0; i < this.validationArr.length; i++) {
          if(this.validationArr[i] == this.opt[i]){
            newArr.push(this.validationArr[i])
            
            
            switch (newArr.length){
              case 1:
                this.$refs.l13.classList.add("black");
                break;

              case 2:
                this.$refs.l13.classList.add("black");
                this.$refs.l14.classList.add("black");
                break;

              case 3:
                this.$refs.l13.classList.add("black");
                this.$refs.l14.classList.add("black");
                this.$refs.l15.classList.add("black");
                break;
              
              case 4:
                this.$refs.l13.classList.add("black");
                this.$refs.l14.classList.add("black");
                this.$refs.l15.classList.add("black");
                this.$refs.l16.classList.add("black");
                break;

            }
          }     
          
        }

        // check if player won 

        if(this.validationArr[0] == this.opt[0] && this.validationArr[1] == this.opt[1] && this.validationArr[2] == this.opt[2] && this.validationArr[3] == this.opt[3]){
          this.modalWIn = true;
        }

        this.validationArr = [];
      }
      // -----------------------------------------------------

    },

    test5(){
      // coder player set initial values for the game
      if(this.opt.length < 4) {
          if(this.special27 && this.special28 && this.special29 && this.special30){
          this.opt.push(this.special27, this.special28, this.special29, this.special30);
        }
      }
      
      // --------------------------------------------------------------
      if(this.selec17 && this.selec18 && this.selec19 && this.selec20){
        if(this.validationArr.length < 4) {
          this.validationArr.push(this.selec17, this.selec18, this.selec19, this.selec20)
        }   
        // --------------------------------------------------------------
      
      
        var arr = [];
        this.validationArr.forEach((x)=>{          
          this.opt.forEach((el) => {
            if (x == el){              
              arr.push(x);

              switch (arr.length){
                case 1:
                  this.$refs.l17.classList.add("yellow");
                  break;

                case 2:
                  this.$refs.l17.classList.add("yellow");
                  this.$refs.l18.classList.add("yellow");
                  break;

                case 3:
                  this.$refs.l17.classList.add("yellow");
                  this.$refs.l18.classList.add("yellow");
                  this.$refs.l19.classList.add("yellow");
                  break;
                
                case 4:
                  this.$refs.l17.classList.add("yellow");
                  this.$refs.l18.classList.add("yellow");
                  this.$refs.l19.classList.add("yellow");
                  this.$refs.l20.classList.add("yellow");
                  break;

              }
            }
          })
        })

        

        var newArr = [];
        for (let i = 0; i < this.validationArr.length; i++) {
          if(this.validationArr[i] == this.opt[i]){
            newArr.push(this.validationArr[i])
            
            
            switch (newArr.length){
              case 1:
                this.$refs.l17.classList.add("black");
                break;

              case 2:
                this.$refs.l17.classList.add("black");
                this.$refs.l18.classList.add("black");
                break;

              case 3:
                this.$refs.l17.classList.add("black");
                this.$refs.l18.classList.add("black");
                this.$refs.l19.classList.add("black");
                break;
              
              case 4:
                this.$refs.l17.classList.add("black");
                this.$refs.l18.classList.add("black");
                this.$refs.l19.classList.add("black");
                this.$refs.l20.classList.add("black");
                break;

              }
          }     
          
        }

        // check if player won 

        if(this.validationArr[0] == this.opt[0] && this.validationArr[1] == this.opt[1] && this.validationArr[2] == this.opt[2] && this.validationArr[3] == this.opt[3]){
          this.modalWIn = true;
        }

        this.validationArr = [];
      }
      // -----------------------------------------------------

    },

    test6(){
      // coder player set initial values for the game
      if(this.opt.length < 4) {
          if(this.special27 && this.special28 && this.special29 && this.special30){
          this.opt.push(this.special27, this.special28, this.special29, this.special30);
        }
      }

      // --------------------------------------------------------------
      if(this.selec21 && this.selec22 && this.selec23 && this.selec24){
        if(this.validationArr.length < 4) {
          this.validationArr.push(this.selec21, this.selec22, this.selec23, this.selec24)
        }   
        // --------------------------------------------------------------
      
      
        var arr = [];
        this.validationArr.forEach((x)=>{          
          this.opt.forEach((el) => {
            if (x == el){              
              arr.push(x);

              switch (arr.length){
                case 1:
                  this.$refs.l21.classList.add("yellow");
                  break;

                case 2:
                  this.$refs.l21.classList.add("yellow");
                  this.$refs.l22.classList.add("yellow");
                  break;

                case 3:
                  this.$refs.l21.classList.add("yellow");
                  this.$refs.l22.classList.add("yellow");
                  this.$refs.l23.classList.add("yellow");
                  break;
                
                case 4:
                  this.$refs.l21.classList.add("yellow");
                  this.$refs.l22.classList.add("yellow");
                  this.$refs.l23.classList.add("yellow");
                  this.$refs.l24.classList.add("yellow");
                  break;

              }
            }
          })
        })

        

        var newArr = [];
        for (let i = 0; i < this.validationArr.length; i++) {
          if(this.validationArr[i] == this.opt[i]){
            newArr.push(this.validationArr[i])
            
            
            switch (newArr.length){
              case 1:
                this.$refs.l21.classList.add("black");
                break;

              case 2:
                this.$refs.l22.classList.add("black");
                this.$refs.l23.classList.add("black");
                break;

              case 3:
                this.$refs.l21.classList.add("black");
                this.$refs.l22.classList.add("black");
                this.$refs.l23.classList.add("black");
                break;
              
              case 4:
                this.$refs.l21.classList.add("black");
                this.$refs.l22.classList.add("black");
                this.$refs.l23.classList.add("black");
                this.$refs.l24.classList.add("black");
                break;

              }
          }     
          
        }

        // check if player won 

        if(this.validationArr[0] == this.opt[0] && this.validationArr[1] == this.opt[1] && this.validationArr[2] == this.opt[2] && this.validationArr[3] == this.opt[3]){
          this.modalWIn = true;
        }

        this.validationArr = [];
      }
      // -----------------------------------------------------

    },

    test7(){
      // coder player set initial values for the game
      if(this.opt.length < 4) {
          if(this.special27 && this.special28 && this.special29 && this.special30){
          this.opt.push(this.special27, this.special28, this.special29, this.special30);
        }
      }

      // --------------------------------------------------------------
      if(this.selec25 && this.selec26 && this.selec27 && this.selec28){
        if(this.validationArr.length < 4) {
          this.validationArr.push(this.selec25, this.selec26, this.selec27, this.selec28)
        }   
        // --------------------------------------------------------------
      
      
        var arr = [];
        this.validationArr.forEach((x)=>{          
          this.opt.forEach((el) => {
            if (x == el){              
              arr.push(x);

              switch (arr.length){
                case 1:
                  this.$refs.l25.classList.add("yellow");
                  break;

                case 2:
                  this.$refs.l25.classList.add("yellow");
                  this.$refs.l26.classList.add("yellow");
                  break;

                case 3:
                  this.$refs.l25.classList.add("yellow");
                  this.$refs.l26.classList.add("yellow");
                  this.$refs.l27.classList.add("yellow");
                  break;
                
                case 4:
                  this.$refs.l25.classList.add("yellow");
                  this.$refs.l26.classList.add("yellow");
                  this.$refs.l27.classList.add("yellow");
                  this.$refs.l28.classList.add("yellow");
                  break;

              }
            }
          })
        })

        

        var newArr = [];
        for (let i = 0; i < this.validationArr.length; i++) {
          if(this.validationArr[i] == this.opt[i]){
            newArr.push(this.validationArr[i])
            
            
            switch (newArr.length){
              case 1:
                this.$refs.l25.classList.add("black");
                break;

              case 2:
                this.$refs.l25.classList.add("black");
                this.$refs.l26.classList.add("black");
                break;

              case 3:
                this.$refs.l25.classList.add("black");
                this.$refs.l26.classList.add("black");
                this.$refs.l27.classList.add("black");
                break;
              
              case 4:
                this.$refs.l25.classList.add("black");
                this.$refs.l26.classList.add("black");
                this.$refs.l27.classList.add("black");
                this.$refs.l28.classList.add("black");
                break;

              }
          }     
          
        }

        // check if player won 

        if(this.validationArr[0] == this.opt[0] && this.validationArr[1] == this.opt[1] && this.validationArr[2] == this.opt[2] && this.validationArr[3] == this.opt[3]){
          this.modalWIn = true;
        }

        this.validationArr = [];
      }
      // -----------------------------------------------------
    },

    test8(){
      // coder player set initial values for the game
      if(this.opt.length < 4) {
          if(this.special27 && this.special28 && this.special29 && this.special30){
          this.opt.push(this.special27, this.special28, this.special29, this.special30);
        }
      }

      // --------------------------------------------------------------
      if(this.selec29 && this.selec30 && this.selec31 && this.selec32){
        if(this.validationArr.length < 4) {
          this.validationArr.push(this.selec29, this.selec30, this.selec31, this.selec32)
        }   
        // --------------------------------------------------------------
      
      
        var arr = [];
        this.validationArr.forEach((x)=>{          
          this.opt.forEach((el) => {
            if (x == el){              
              arr.push(x);

              switch (arr.length){
                case 1:
                  this.$refs.l29.classList.add("yellow");
                  break;

                case 2:
                  this.$refs.l29.classList.add("yellow");
                  this.$refs.l30.classList.add("yellow");
                  break;

                case 3:
                  this.$refs.l29.classList.add("yellow");
                  this.$refs.l30.classList.add("yellow");
                  this.$refs.l31.classList.add("yellow");
                  break;
                
                case 4:
                  this.$refs.l29.classList.add("yellow");
                  this.$refs.l30.classList.add("yellow");
                  this.$refs.l31.classList.add("yellow");
                  this.$refs.l32.classList.add("yellow");
                  break;

              }
            }
          })
        })

        

        var newArr = [];
        for (let i = 0; i < this.validationArr.length; i++) {
          if(this.validationArr[i] == this.opt[i]){
            newArr.push(this.validationArr[i])
            
            
            switch (newArr.length){
              case 1:
                this.$refs.l29.classList.add("black");
                break;

              case 2:
                this.$refs.l29.classList.add("black");
                this.$refs.l30.classList.add("black");
                break;

              case 3:
                this.$refs.l29.classList.add("black");
                this.$refs.l30.classList.add("black");
                this.$refs.l31.classList.add("black");
                break;
              
              case 4:
                this.$refs.l29.classList.add("black");
                this.$refs.l30.classList.add("black");
                this.$refs.l31.classList.add("black");
                this.$refs.l32.classList.add("black");
                break;

              }
          }     
          
        }

        // check if player won 

        if(this.validationArr[0] == this.opt[0] && this.validationArr[1] == this.opt[1] && this.validationArr[2] == this.opt[2] && this.validationArr[3] == this.opt[3]){
          this.modalWIn = true;
        }

        this.validationArr = [];
      }
      // -----------------------------------------------------
    }

  },
  watch: {
    
  },
}
</script>

<style>

.blue {
  background-color: blue;
}

.red {
  background-color: red;
}

.white {
  background-color: white;
}

.yellow {
  background-color: yellow;
}

.green {
  background-color: green;
}

.black {
  background-color: black;
}

.hv {
  cursor: pointer;
}



</style>
