---
layout: page
permalink: /maquinesTermiques/
---

<h1> Màquines tèrmiques </h1>

Una **màquina tèrmica** és un invent capaç de transformar l'**energia tèrmica** (la calor) en **energia mecànica** (moviment). Sense aquestes màquines, la Revolució Industrial no hauria existit i avui no tindríem cotxes, trens ni avions!

Anem a veure les dues màquines tèrmiques més famoses de la història: la màquina de vapor i el motor de quatre temps.

<h3> La Màquina de Vapor</h3>

La màquina de vapor va ser la gran protagonista de la Revolució Industrial. S'anomena de "combustió externa" perquè el foc que genera la calor està fora del motor (en una caldera).

<h4>Com funciona?</h4>
El funcionament és molt enginyós i es resumeix en tres passos:
1. **S'escalfa aigua** en una caldera cremant carbó o fusta fins que es converteix en vapor.
2. Aquest **vapor a molta pressió** viatja per uns tubs fins a un cilindre.
3. Dins del cilindre, el vapor té tanta força que **empeny un pistó**. Aquest moviment del pistó està connectat a una roda, fent-la girar.

[Image of schematic diagram of a steam engine]

<figure style="text-align: center;">
  <img src="/assets/images/maquinesTermiques/partsMaquinaVapor.png" alt="Esquema d'una màquina de vapor" width="80%">
</figure>

Aquí pots veure com el moviment recte del pistó es transforma en un moviment circular gràcies a un mecanisme anomenat biela-manivela.

<div style="text-align: center;">
  <img src="/assets/images/maquinesTermiques/maquinaVapor.gif" alt="Animació del funcionament de la màquina de vapor" width="70%">
</div>

<h3>El Motor de Quatre Temps</h3>

Aquest és el motor que porten la majoria de cotxes i motos actuals (de benzina o dièsel). S'anomena de "combustió interna" perquè el foc (l'explosió) passa **a l'interior** del mateix motor, just dins del cilindre.

<h4>Les 4 fases del motor</h4>
Per aconseguir moviment, el motor repeteix contínuament un cicle de 4 passos o "temps":

1. **Admissió:** S'obre una vàlvula i entra una barreja d'aire i benzina dins del cilindre. El pistó baixa.
2. **Compressió:** Es tanquen les vàlvules. El pistó puja i "aixafa" la barreja, escalfant-la molt.
3. **Explosió (o Expansió):** Una peça anomenada bugia fa una petita guspira. La benzina explota amb molta força i empeny el pistó cap avall violentament. **(Aquest és l'únic temps que dóna força al motor!).**
4. **Escapament:** S'obre una altra vàlvula. El pistó torna a pujar per expulsar els fums de l'explosió cap al tub d'escapament. I el cicle torna a començar!

A continuació pots veure les parts d'un motor de quatre temps i les quatre fases dibuixades.

<figure style="text-align: center;">
  <img src="/assets/images/maquinesTermiques/partsMotor.png" alt="Les parts del motor tèrmic" width="90%">
  <img src="/assets/images/maquinesTermiques/fasesMotor.png" alt="Els 4 temps del motor tèrmic" width="90%">
</figure>

Fixa't en aquesta animació per entendre com les vàlvules s'obren i es tanquen al ritme adequat i com l'explosió fa moure l'engranatge inferior (el cigonyal).

<div style="text-align: center;">
  <img src="/assets/images/maquinesTermiques/animacioMotor.gif" alt="Animació d'un motor de 4 temps" width="60%">
</div>

<div style="background-color: #f4f4f9; padding: 25px; border-radius: 10px; border: 1px solid #ddd; margin-top: 40px;">
  <h3 style="margin-top: 0; color: #333;">🧠 Posa a prova el que has après!</h3>
  <p>Respon aquestes 4 preguntes per veure si domines les màquines tèrmiques:</p>

  <form id="quiz-maquines">
    <div style="margin-bottom: 15px;">
      <p><strong>1. Quina transformació d'energia fa una màquina tèrmica?</strong></p>
      <label><input type="radio" name="q1" value="a"> a) Transforma el moviment en calor.</label><br>
      <label><input type="radio" name="q1" value="b"> b) Transforma l'energia tèrmica (calor) en energia mecànica (moviment).</label><br>
      <label><input type="radio" name="q1" value="c"> c) Transforma l'energia elèctrica en energia tèrmica.</label>
    </div>

    <div style="margin-bottom: 15px;">
      <p><strong>2. Per què diem que la màquina de vapor és de "combustió externa"?</strong></p>
      <label><input type="radio" name="q2" value="a"> a) Perquè el foc que escalfa l'aigua es fa fora del cilindre del motor (a la caldera).</label><br>
      <label><input type="radio" name="q2" value="b"> b) Perquè el vapor s'escapa cap a l'exterior.</label><br>
      <label><input type="radio" name="q2" value="c"> c) Perquè funciona a l'aire lliure.</label>
    </div>

    <div style="margin-bottom: 15px;">
      <p><strong>3. Quin és l'ordre correcte de les 4 fases d'un motor de cotxe?</strong></p>
      <label><input type="radio" name="q3" value="a"> a) Admissió, Explosió, Compressió i Escapament.</label><br>
      <label><input type="radio" name="q3" value="b"> b) Compressió, Admissió, Escapament i Explosió.</label><br>
      <label><input type="radio" name="q3" value="c"> c) Admissió, Compressió, Explosió i Escapament.</label>
    </div>

    <div style="margin-bottom: 20px;">
      <p><strong>4. En quina d'aquestes fases el motor rep impuls i produeix força de veritat?</strong></p>
      <label><input type="radio" name="q4" value="a"> a) En l'Admissió.</label><br>
      <label><input type="radio" name="q4" value="b"> b) En l'Explosió.</label><br>
      <label><input type="radio" name="q4" value="c"> c) En l'Escapament.</label>
    </div>

    <button type="button" onclick="comprovaTest()" style="background-color: #28a745; color: white; border: none; padding: 10px 20px; font-size: 16px; border-radius: 5px; cursor: pointer;">Comprova les meves respostes</button>
  </form>

  <p id="resultat-test" style="font-weight: bold; font-size: 18px; margin-top: 20px;"></p>
</div>

<script>
  function comprovaTest() {
    let encerts = 0;
    const total = 4;

    // Recollim les respostes seleccionades
    const q1 = document.querySelector('input[name="q1"]:checked');
    const q2 = document.querySelector('input[name="q2"]:checked');
    const q3 = document.querySelector('input[name="q3"]:checked');
    const q4 = document.querySelector('input[name="q4"]:checked');

    // Comprovem les respostes correctes
    if (q1 && q1.value === "b") encerts++;
    if (q2 && q2.value === "a") encerts++;
    if (q3 && q3.value === "c") encerts++;
    if (q4 && q4.value === "b") encerts++;

    // Mostrem el resultat
    const missatge = document.getElementById("resultat-test");
    if (encerts === total) {
      missatge.innerHTML = "🏆 Excel·lent! Has encertat totes les respostes (" + encerts + "/" + total + "). Has entès perfectament les màquines tèrmiques.";
      missatge.style.color = "#28a745"; // Verd
    } else if (encerts > 0) {
      missatge.innerHTML = "👍 Bé! Has tingut " + encerts + " encerts de " + total + ". Repassa una mica la teoria i torna a intentar-ho per aconseguir el 4 de 4!";
      missatge.style.color = "#d39e00"; // Groc fosc/Taronja
    } else {
      missatge.innerHTML = "😅 Vaja, sembla que no has encertat cap resposta (0/4). Llegeix l'explicació de nou, segur que a la propera et surt millor!";
      missatge.style.color = "#dc3545"; // Vermell
    }
  }
</script>
