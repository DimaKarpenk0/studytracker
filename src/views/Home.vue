<template>
  <body>
    <div class="wrapper">
      <div class="content">
        <div class="main_container" id="app">
      
          <div class="back">
            <a href="#" class="back_btn"></a>
          </div>
      
          <header class="header">
            <div class="header_container">
              <p class="header_title">Посещаемость</p>
            </div>
          </header>
      
          <div class="couple_data">
            <p>Лекция/ практ. з./ лаб р дата</p>
            <p>Группа название предмета</p>
          </div>
          
          <div class="table">
            <table>
              <thead>
                <tr>
                  <td width="75%">ФИО</td>
                  <td>Ометка</td>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <td></td>
                  <td></td>
                </tr>
              </tbody>
            </table>
          </div>
      
          <div class="bottom_btn">
            <button class="cancel_btn">Отмена</button>
            <button class="save_btn">Сохранить</button>
          </div>

        </div>      
      </div>
    </div>
  </body>
</template>

<script>
  export default {
    name: 'Home_1'
  }
  
</script>