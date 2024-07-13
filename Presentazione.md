---
theme: gaia
_class: lead
paginate: false <!-- disabilita la numerazione delle pagine -->
backgroundColor: #fff
backgroundImage: url('https://marp.app/assets/hero-background.svg')
lang: it-it

style: |

    div{
        font-size: 29pt;
    }

    .two-columns{
        display: grid;
        grid-template-columns: 1fr 1fr;
        column-gap: 100px;
    }
---

# <!-- fit -->**Filtro crossover**

## Giacomo Errani e Paolo Forni

---
<!-- class: lead -->

# Obiettivo dell'esperimento

<div class="two-columns">
    <div style=" display: flex; justify-content: center; align-items: center;">
        Verificare entro quali limiti il modello teorico descrive il comportamento
        di un circuito crossover reale
    </div>
    <img src="report\images\cross_reduced_range_theoric.png">
</div>

---

# Scopo del circuito

<div class="two-columns">
    <div>
        <div style="height: 70%; display: flex; justify-content: center; align-items: center;">
            Il filtro crossover è un circuito che separa un segnale in ingresso nelle sue componenti in base alla frequenza.

Utilizza un filtro passa alto (Tweeter) e uno passa basso (Woofer) in parallelo, con due resistenze di carico uguali (100 Ohm). La resistenza dell’induttanza è trascurabile (1 Ohm), così come quella della capacità.
        </div>
    </div>
    <img src="report\images\Schema_crossover.png">
</div>

---

# Il circuito

<div class="two-columns">
    <div>
        <h4>I nostri valori</h4>
        <div style="height: 70%; display: flex; justify-content: center; align-items: center;">
            R ≃ 100 Ω<br>
            C ≃ 1 μF<br>
            L ≃ 10 mH<br>
            R_gen ≃ 50 Ω
        </div>
    </div>
    <img src="report\images\Schema_crossover.png">
</div>

---



---
![width:200px](report\images\cross_dataonly.png)

# **Marp**

Markdown Presentation Ecosystem

https://marp.app/
