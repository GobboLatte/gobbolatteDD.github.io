# The Hamlet Roster
<style>
  .roster-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: flex-start;
  }
  .roster-grid a {
    text-decoration: none;
    color: inherit;
  }
  .hero-card {
    width: 260px;
    height: 100%;
    min-height: 250px; /* Forces cards to stay identical in height */
    background: #141414;
    border: 1px solid #3a1111;
    border-left: 5px solid #cd1010;
    border-radius: 6px;
    overflow: hidden;
    box-shadow: 0 4px 6px rgba(0,0,0,0.4);
    transition: transform 0.15s ease, box-shadow 0.15s ease;
    display: flex;
    flex-direction: column; /* Stretches the interior content down */
  }
  .hero-card img {
    width: 100%;
    height: 160px; /* Enforces uniform image crop boxes */
    object-fit: cover;
    object-position: center 15%;
    display: block;
  }
  .hero-card-content {
    padding: 12px;
    flex-grow: 1; /* Pushes the card contents to fill remaining space */
    display: flex;
    flex-direction: column;
  }
  .hero-title {
    font-weight: bold;
    color: #e2d6b5;
    font-size: 1.1em;
  }
  .hero-roles {
    color: #bfa67a;
    font-size: 0.85em;
    margin-top: 4px;
    line-height: 1.3;
  }
</style>

> Modded Darkest Dungeon Heroes

---

<div class="roster-grid">

  <!-- Beastmaster -->
  <a href="/Beastmaster" style="text-decoration: none; color: inherit;">
    <div class="hero-card">
      <img src="_assets/Beastmaster/Beastmaster Art.webp" alt="Beastmaster">
      <div class="hero-card-content">
        <div class="hero-title">Beastmaster</div>
        <div class="hero-roles">Corpses / Stealth / Versatile</div>
      </div>
    </div>
  </a>

  <!-- Falconer -->
  <a href="/Falconer" style="text-decoration: none; color: inherit;">
    <div class="hero-card">
      <img src="_assets/Falconer/Falconer Art.webp" alt="Falconer">
      <div class="hero-card-content">
        <div class="hero-title">Falconer</div>
        <div class="hero-roles">Bleed / Debuff / Ranged</div>
      </div>
    </div>
  </a>

<!-- Monk -->
  <a href="/Monk" style="text-decoration: none; color: inherit;">
    <div class="hero-card">
      <img src="_assets/Monk/Monk Portrait Art.png" alt="Monk">
      <div class="hero-card-content">
        <div class="hero-title">Monk</div>
        <div class="hero-roles">Healer / Mobile / Support</div>
      </div>
    </div>
  </a>

  <!-- Revenant -->
  <a href="/Revenant" style="text-decoration: none; color: inherit;">
    <div class="hero-card">
      <img src="_assets/Revenant/RevenantClass.webp" alt="Revenant">
      <div class="hero-card-content">
        <div class="hero-title">Revenant</div>
        <div class="hero-roles">Bleed / Frontline / Tank</div>
      </div>
    </div>
  </a>

<!-- Therapist -->
  <a href="/Therapist" style="text-decoration: none; color: inherit;">
    <div class="hero-card">
      <img src="_assets/Therapist/Therapist Art.png" alt="Therapist">
      <div class="hero-card-content">
        <div class="hero-title">Therapist</div>
        <div class="hero-roles">Debuff / Stress Healer / Support</div>
      </div>
    </div>
  </a>

<!-- Twilight Knight -->
  <a href="/Twilight Knight" style="text-decoration: none; color: inherit;">
    <div class="hero-card">
      <img src="_assets/Twilight Knight/Twilight Knight Art.png" alt="Twilight Knight">
      <div class="hero-card-content">
        <div class="hero-title">Twilight Knight</div>
        <div class="hero-roles">Frontline / Melee / Stress Healer</div>
      </div>
    </div>
  </a>

<!-- Veiled -->
  <a href="/Veiled" style="text-decoration: none; color: inherit;">
    <div class="hero-card">
      <img src="_assets/Veiled/Veiled Portrait Art.webp" alt="Veiled">
      <div class="hero-card-content">
        <div class="hero-title">Veiled</div>
        <div class="hero-roles">Death's Door / Healer / Support</div>
      </div>
    </div>
  </a>

</div>
