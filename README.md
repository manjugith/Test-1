                <figcaption onclick="package('modal', '1', '')">all text-focus-in">Want to dive deeper? Get the source code on Github</h3>
            <a href="https://github.com/bboysdreamsfell/comingsoon-webpage-minimalistic" class="btn btn_1 text-focus-in flex align_center" target="_blank"><iconify-icon icon="mdi:github"></iconify-icon> - GitHub</a>
        </article>
    </footer>
    
    <!--MODAL-->
    <div class="modal text-focus-in" id="modal">
        <section class="video swing-in-top-fwd">
            <iconify-icon icon="solar:play-bold" class="medium"></iconify-icon>
        </section>
    </div>

</main>



<!--REMOVE THIS-->
<aside class="credits">
  Credits: 
  <a href="https://animista.net/" target="_blank"><iconify-icon icon="twemoji:letter-a"></iconify-icon> Animista</a>
</aside>
/*CREDITS*/
.credits{
    background-color:var(--black);
    color:var(--white);
    padding:0.3rem;
    position:fixed;
    z-index:99999 !important;
    bottom:1rem;
    right:0;
    font-size:13px;
    display:flex;
    align-items:center;
    flex-wrap:wrap;
    flex-direction:row;
    max-width:200px;
    gap:10px;
}

.credits a{
    color:var(--white);
    opacity:0.6;
    position:relative;
    font-size:13px;
    display:flex;
    align-items:center;
    gap:2px;
}

.credits a:not(:last-child):after{
    content:",";
}
