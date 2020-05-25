var mec = false;
var bojoval = false;
var zivot = true;

function myFunction0() {
    if (zivot == true) {
        document.getElementById("text0").innerHTML = 'Pivo krásně pění a jak ti chutná! Jsi opilý a lichou chůzí jdeš domů. Tady jsi svoji milou nenašel.' +
        '<br> Chceš hrát hru znovu? <br> <button type="button" onclick="reset()">Reset</button><br>';
        document.getElementById("text1").innerHTML = '';
        document.getElementById("text2").innerHTML = '';
        zivot = false;
    } else {}
}

function myFunction1() {
    if (zivot == true) {
        document.getElementById("text0").innerHTML = 'Zde bohužel nic není, jen zápach a pár krys. Vydal si se špatnou cestou.' +
        '<br> Chceš hrát hru znovu? <br> <button type="button" onclick="reset()">Reset</button><br>';
        document.getElementById("text1").innerHTML = '';
        document.getElementById("text2").innerHTML = '';
        zivot = false;
    } else {}
}

function myFunction2() {
    if (zivot == true && bojoval == false) {
        document.getElementById("text0").innerHTML = "Dorazil si do kovárny a vyprávíš svůj příběh kováři." +
            '<br> Kováři se tě zželelo a tak ti ukoval velký a silný meč. Tím obra porazíš! <br> <button type="button" onclick="myFunction3()">Jít do jeskyně</button><br>';
        mec = true;
    } else {}
}

function myFunction3() {
    if (zivot == true) {
        if (mec == 0) {
            document.getElementById("text0").innerHTML = "Jsi v jeskyni, ale nemáš žádnou zbraň. Jdi se podívat jinam.";
        } else {
            document.getElementById("text1").innerHTML = 'Došel si do jeskyně a proti tobě stojí obr s tvojí ženou v pazourech.. „Kdo si a co tu děláš?! Tebe si dám k obědu!“ BOJUJ!'+
            '<button type="button" onclick="boj()">Bojovat</button><br>';
        

        }
    } else {}
}

function reset() {
    document.getElementById("text0").innerHTML = "";
    document.getElementById("text1").innerHTML = "";
    document.getElementById("text2").innerHTML = "";
    mec = false;
    bojoval = false;
    zivot = true;
}

function boj() {
    if (bojoval == false) {
        var rn = Math.floor(Math.random() * 10);
        if (rn == 5 || rn == 6) {
            document.getElementById("text1").innerHTML = 'Bohužel si neobstál, obr vyhrál a tvou ženu donutil ke sňatku.'; +
            '<br> Chceš hrát hru znovu? <br> <button type="button" onclick="reset()">Reset</button><br>';
            zivot = false;
            bojoval = true;
        } else {
            document.getElementById("text1").innerHTML = 'Bojoval si s obrem statečně až si ho nakonec skolil! ' +
                'Tvá žena tě líbá a objímá! Dobře to dopadlo! <br>' +
                'Chceš hru hrát znovu? <br> <button type="button" onclick="reset()">Reset</button><br>';
            bojoval = true;
        }
    } else {
        if (zivot == false) {
            document.getElementById("text2").innerHTML = 'Jsi mrtev';
        } else {
            document.getElementById("text2").innerHTML = 'Z obra zbyla jen fašírka. Dobrá práce! Vracíš se s ženou domů, určitě tě nemine odměna! <br>' +
            'Chceš hrát hru znovu? <br> <button type="button" onclick="reset()">Reset</button><br>';
        }

    }
}
