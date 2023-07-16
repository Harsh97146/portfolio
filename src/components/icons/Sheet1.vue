<script setup lang="ts">

</script>

<template>
  <div class="main">
    <div class="title">
      <div class="sub">
        TEX INVOICE
      </div>
      <div class="dic">
        <div class="title2">Original Copy</div>
        <div>This is computer generate invoice</div>
      </div>
    </div>
    <div class="contant">
        <div class="left">
          <img src="https://1000logos.net/wp-content/uploads/2021/10/Batman-Logo-768x432.png" alt="">
          <div class="text1">
            GatikAI Technologies Pvt. Ltd
          </div>
          <div class="text2">
            +91-8888888888
          </div>
          <div class="text2 adds">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iure, error cupiditate, 
          </div>
          <div class="text1 gst">
            GSTIN: 08ABCDE1234A1ZZ
          </div>
        </div>
        <div class="right">
          <div class="part1">
            <div class="col">
              <span class="text2 ab">
                Invoice No
              </span><br>
              <span class="text1">
                INV/JPR/FY23
              </span>
            </div>
            <div class="col">
              <span class="text2 ab">
                Total Amount
              </span><br>
              <span class="text1">
                5,90,565
              </span>
            </div>
            <div class="col">
              <span class="text2 ab">
                Buyer Order No.
              </span><br>
              <span class="text1">
                P/12/JPR/FY23
              </span>
            </div>
            <div class="col">
              <span class="text2 ab">
                Dispatch No.
              </span><br>
              <span class="text1">
                2343469211231213
              </span>
            </div>
            <div class="col2">
              <span class="text2">
                Dispatch through
              </span><br>
              <span class="text1">
                BlueDart
              </span>
            </div>
          </div>
          <div class="part2">
            <div class="col3">
              <span class="text2">
                Issue Date
              </span><br>
              <span class="text1">
               14/01/2023
              </span>
            </div>
            <div class="col3">
              <span class="text2">
                Due Date
              </span><br>
              <span class="text1">
                24/01/2023
              </span>
            </div>
            <div class="col3">
              <span class="text2">
                Buyer Order Date
              </span><br>
              <span class="text1">
                05/01/2023
              </span>
            </div>
            <div class="col3">
              <span class="text2">
                Dispatch Date
              </span><br>
              <span class="text1">
                14/01/2023
              </span>
            </div>
            <div class="col4">
              <span class="text1">
                E-way Bill ref:
              </span>
            </div>
          </div>
        </div>
      </div>
      <div class="addres"><br>
        <div class="left2">
          <div class="text2">
            <br>
            Billing Address
          </div>
          <div class="text1">
            Gaurav Sharma <br>
            Divam Technologies
          </div>
          <div class="text2">
            0141-12312312 <br>
            F35 Dwarika Tower, Vidhyadhar Nagar, Jaipur, <br>
            Rajasthan-302039
          </div><br><br>
          <div class="text1">
            GSTIN: 08AAICD4100HZZ
          </div>
        </div>
        <div class="right2">
          <div class="text2">
            <br>
            Shipping Address
          </div>
          <div class="text1">
            Sulbha Sharma <br>
            +91-8888888888
          </div>
          <br>
          <br>

          <div class="text2">
            A88/12123, Shiv Nagar 1, Near Goras <br>
            Bhandar, Road No. 1, Murlipura, Jaipur, <br>
            Rajasthan-302039
          </div>
        </div>
      </div>
      <br>
      <div class="tb">
        <table>
          <tr>
            <th style="width: 5%;">s. <br> NO.</th>
            <th style="width: 40%;">Item</th>
            <th style="width: 10%;">Qyt</th>
            <th style="width: 10%;">Rate@</th>
            <th>Amount</th>
            <th>Discount</th>
            <th>Gst</th>
            <th style="width: 10%;">Net Amount</th>
          </tr>
          <tr>
            <td>1.</td>
            <td>Sari 1 <br>Banarsi wali sari HSN: 12312312</td>
            <td class="td1">1500pcs</td>
            <td class="td1">1,00,000.00</td>
            <td class="td1">15,00,000.00</td>
            <td class="td1">-10,00,000</td>
            <td class="td1">18%</td>
            <td class="td1">17,58,20,000.00</td>
          </tr>
          <tr>
            <td>2.</td>
            <td>Sari 2 <br>Culcutta cottan wali sari HSN: 12312312</td>
            <td class="td1">15pcs</td>
            <td class="td1">350.00</td>
            <td class="td1">5,250.00</td>
            <td class="td1">-250</td>
            <td class="td1">18%</td>
            <td class="td1">5,900.00</td>
          </tr>
          <tr>
            <td>3.</td>
            <td>Kurti 1 <br>Chiken Kari HSN:82312312</td>
            <td class="td1">200pcs</td>
            <td class="td1">1,000.00</td>
            <td class="td1">2,00,000.00</td>
            <td class="td1">-50,000</td>
            <td class="td1">18%</td>
            <td class="td1">1,77,000.00</td>
          </tr>
          <tr>
            <td>4.</td>
            <td>Kurti 2 <br>HSN: 12312312</td>
            <td class="td1">2500pcs</td>
            <td class="td1">1,200.00</td>
            <td class="td1">30,00,000.00</td>
            <td class="td1">-25,000</td>
            <td class="td1">18%</td>
            <td class="td1">35,10,500.00</td>
          </tr>
          <tr>
            <td>5.</td>
            <td>Kurti 3 <br>HSN: 12312312</td>
            <td class="td1">355pcs</td>
            <td class="td1">450.35</td>
            <td class="td1">1,59,874.25</td>
            <td class="td1">-10,000</td>
            <td class="td1">18%</td>
            <td class="td1">1,76,851.62</td>
          </tr>
          <tr>
            <td colspan="2" class="td1">Total</td>
            <td class="td1">4570pcs</td>
            <td></td>
            <td>15,33,65,124.25</td>
            <td>10,85,250</td>
            <td></td>
            <td>17,96,90,251.62</td>
          </tr>
        </table>
        <div class="sum">
          <div class="left3"> <br> <br>
            <div class="text2">Amount chargeable in words:</div>
           <div class="text1"> Five Lacs Nighty Thousands Five Hundred Sixty Five <br>
            INR Only</div>
          </div>
          <div class="right3">
            <div class="upper">
              <div class="words">
              Extra Discount <br>
              Delivery Charges <br>
              Round Off
            </div>
            <div class="amount">
              -635.25 <br>
              1200.21 <br>
              0.42
            </div>
            </div>
            <div class="total">
              <div class="word text1">Grand Total</div>
              <div class="total1 text1">17,96,90,815.00</div>
            </div>
          </div>
        </div>
      </div>
      <div class="table2">
        <table style="width: 100%; text-align: center;">
          <tr>
            <th rowspan="2" style="width: 20%;">HSN/SAC</th>
            <th rowspan="2" style="width: 20%;">Taxable Amount</th>
            <th colspan="2" style="width: 20%;">CGST</th>
            <th colspan="2" style="width: 20%;">SGST</th>
            <th rowspan="2" style="width: 20%;">TOtal Tax Amount</th>
          </tr>
          <tr>
            <td>Rate</td>
            <td>Amount</td>
            <td>Rate</td>
            <td>Amount</td>
          </tr>
          <tr>
            <td>12345678</td>
            <td>3,00,000</td>
            <td>9%</td>
            <td>27,000</td>
            <td>9%</td>
            <td>27,000</td>
            <td>54,000</td>
          </tr>
          <tr>
            <td>82345678</td>
            <td>2,00,000</td>
            <td>9%</td>
            <td>18,000</td>
            <td>9%</td>
            <td>18,000</td>
            <td>54,000</td>
          </tr>
          <tr>
            <td>Total</td>
            <td>5,00,000</td>
            <td colspan="2">45,000</td>
            <td colspan="2">45,000</td>
            <td>90,000</td>
          </tr>
        </table>
      </div>
      <div class="terms">
        Term & Conditions: <br>
        1. Payment Terms: The payment for the goods or services sold under this invoice is due 10 days from the date of the invoice. Late payments will be subject to a 1% interest charge per month. <br>
        2. Delivery: The goods or services will be delivered, such as "within 5 business days of the date of this invoice" or "upon receipt of payment". The buyer assumes responsibility for all shipping and handling charges.
      </div>
      <div class="last">
        <div class="bank">
          <div class="text1">Bank Details:</div>
          <div class="">GatikAI Technologies Pvt. Ltd <br>
          HDFC Bank - Vidhyadhar Nagar - Jaipur- 302039 <br>
          A/C No. 123123123123123 <br>
          IFSC: HDFC004322323
          UPI: somehign@okhdfc
        </div>
        </div>
        <div class="qr">
          <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d0/QR_code_for_mobile_English_Wikipedia.svg/640px-QR_code_for_mobile_English_Wikipedia.svg.png" alt="">
        </div>
        <div class="comp">
          <div class="name">for GatikAI Technologies Pvt. Ltd.</div>
          <div class="auth">
            Authorised signatory
          </div>
        </div>
      </div>
  </div>
</template>

<style scoped>
 .main{
  width: 900px;
  height: 800px;
  margin: auto;
  
 }
 .title{
  display: flex;
  justify-content: space-between;
 }

 .sub{
  font-size: x-large ;
  font-weight: 600;
 }
 .dic{
  text-align: right;
 }
 .title2{
  font-size: larger;
  font-weight: 600;
 }
 .left>img{
  width: 100px;
  margin-left: 20px;
  margin-top: 5px;
 }
 .contant{
  display: flex;
 }
 .left{
  width: 450px;
  height: 300px;
  border: 2px solid black;
 }
 .right{
  width: 450px;
  height: 300px;
  border: 2px solid black;
  border-left: none;
  display: flex;
 }
 .text1{
  font-size: larger;
  font-weight: 600;
  margin-left: 10px;
 }
 .text2{
  font-size: larger;
  margin-left: 10px;
 }
 .adds{
  margin-top: 20px;
 }
 .gst{
  margin-top: 20px;
 }
 .part1{
  width: 200px;
  height: 300px;
  border-right: 2px solid black;
 }
 .col{
  width: 200px;
  height: 60px;
  border-bottom: 2px solid black;
 }
 .col2{
  width: 200px;
  height: 60px;
 }
 .col3{
  width: 250px;
  height: 60px;
  border-bottom: 2px solid black;
 }
 .col4{
  width: 250px;
  height: 60px;
 }
 .addres{
  width: 100%;
  height: 200px;
  display: flex;
 }
 .left2{
  width: 50%;
  height: 220px;
  /* margin-top: 20px; */
  border-left: 2px solid black;
 }
 .right2{
  width: 50%;
  height: 220px;
  border-right: 2px solid black;
 }
 table, th, td {
  border: 2px solid black;
  border-collapse: collapse;
}
.td1{
  text-align: right;
}
.sum{
  display: flex;
}
.left3{
  width: 50%;
  height: 120px;
  border-left: 2px solid black;
}
.right3{
  width: 50%;
  height: 120px;
  border-right: 2px solid black;
}
.upper{
  display: flex;
}
.words{
  width: 70%;
  height: 100px;
  text-align: right;
  margin-top: 20px;
}
.amount{
  width: 30%;
  height: 100px;
  text-align: right;
  margin-top: 20px;
  
}
.total{
  display: flex;
  margin-top: -30px;
  background-color: rgba(0, 0, 0, 0.189);
}
.total1{
  width: 50%;
  text-align: right;
}
.terms{
  font-size: x-small;
}
.last{
  display: flex;
  /* justify-content: space-between; */
}
.bank{
  margin-top: 50px;
  width: 350px;
}
.qr{
  width: 200px;
  height: auto;

}
.qr>img{
  width: 100%;
  height: auto;
}
.comp{
  margin-top: 50px;
  width: 400px;
  height: 130px;
  border: 2px solid black; 
  text-align: right;
}
.auth{
  margin-top:90px
}
</style>
