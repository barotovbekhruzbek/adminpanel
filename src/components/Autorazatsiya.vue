<template>
  <div class="main">
      <div class="container">
          <div class="part">
                <p>Имя сотрудника</p>
                <input type="text" placeholder="Enter your name...">
                <p>Регистрированный номер телефона</p>
                <input type="text" placeholder="+_ (___) ___-____">
          </div>
         <div class="radio">
              <div class="value-radio">
              <input type="radio" id="in" name="top">
              <label for="in">Электрик</label>
          </div>


           <div class="value-radio">
              <input type="radio" id="ox" name="top">
              <label for="ox">Охрана</label>
          </div>

             <div class="value-radio">
              <input type="radio" id="mo" name="top">
              <label for="mo">Монтёр</label>
          </div>

          
             <div class="value-radio">
              <input type="radio" id="te" name="top">
              <label for="te">Тест</label>
          </div>
         </div>
         <p class="title">Описание</p>
         <textarea name="" id="" cols="50" rows="15" placeholder="Placeholder text..."></textarea>
         <div class="btn">
             <button type="button">
                 Добавить
             </button>
         </div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.main{
    width: 100%;
    .container{
        max-width: 600px;
        margin: 0 auto;

        .part{
            padding-top: 170px;
            p{
                font-weight: 400;
                font-size: 14px;
                line-height: 16px;
                color: #333333;

            }
            input{
                width: 500px;
                height: 45px;
                padding-left: 10px;
            }
        }
        .radio{
            padding-top: 50px;
            display: flex;
            padding-bottom: 50px;
            
            .value-radio{
                &:first-child{
                    padding-left: 0px;
                }
                display: flex;
                align-items: center;
                padding-left: 50px;
                #in, #ox, #mo, #te{
                    width: 24px;
                    height: 24px;
                }
            }
        }

    }
}

.title{
    font-size: 14px;
    line-height: 16px;


    color: #333333;

}
.btn{
    padding-top: 50px;
   margin-left: 400px;
    button{
            background: #118844;
            border-radius: 5px;
            color: white;
            padding: 10px 5px;
            border: 0;
    }
}


</style>