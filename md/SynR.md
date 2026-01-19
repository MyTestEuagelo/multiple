## Design and Finite Element Analysis of a Reluctance Machine
<div style="display:flex; flex-direction:column; gap:0.6rem;">
    <div class="project-tags" style="display:flex; align-items:center; gap:1rem;">
        <span class="timeline-meta" style="display:inline-flex; align-items:center; gap:0.5rem;">
            <svg viewBox="0 0 24 24" width="14" height="14" aria-hidden="true" style="opacity:1;">
                <rect x="3" y="4" width="18" height="18" rx="2"
                      fill="none" stroke="currentColor" stroke-width="1.5"/>
                <path d="M16 2v4M8 2v4M3 10h18"
                      fill="none" stroke="currentColor" stroke-width="1.5"/>
            </svg>
            February 10, 2025
        </span>
        <div style="zoom:0.8; display:flex; align-items:center; gap:0.5rem; transform: translateY(1px);">
            <span class="tag tag-safety">fem</span>
            <span class="tag tag-conference">MAtlab</span>
            <span class="tag tag-arxiv">Autocad</span>
            <span class="tag tag-workshop">blender</span>
        </div>
    </div>
    <div style="height:1.5px; width:100%; background: currentColor; opacity:0.15; margin-bottom: 0.5rem"></div>
   
</div>

<!-- src="../assets/3D_machine.glb"  autoplay auto-rotate-->
<model-viewer src="../assets/3D_machine.glb" ar ar-modes="webxr scene-viewer quick-look" camera-controls tone-mapping="neutral" poster="poster.webp" shadow-intensity="0.5"  camera-orbit="-39deg 81.78deg 107.8m" field-of-view="22.98deg" >
    <button class="Hotspot" slot="hotspot-1" data-surface="4 0 589 485 602 0.173 0.003 0.824" data-visibility-attribute="visible">
        <div class="HotspotAnnotation">Magnets</div>
    </button><button class="Hotspot" slot="hotspot-2" data-surface="3 0 230170 230185 230384 0.819 0.112 0.070" data-visibility-attribute="visible">
        <div class="HotspotAnnotation">Rotor</div>
    </button><button class="Hotspot" slot="hotspot-3" data-surface="3 0 238953 238962 239019 0.416 0.315 0.269" data-visibility-attribute="visible">
        <div class="HotspotAnnotation">Stator</div>
    </button><button class="Hotspot" slot="hotspot-4" data-surface="0 0 1989 1950 1986 0.367 0.231 0.402" data-visibility-attribute="visible">
        <div class="HotspotAnnotation">Windings</div>
    </button>
    <div class="progress-bar hide" slot="progress-bar">
        <div class="update-bar"></div>
    </div>
    <!-- <button slot="ar-button" id="ar-button">
        View in your space
    </button>
    <div id="ar-prompt">
        <img src="https://modelviewer.dev/shared-assets/icons/hand.png">
    </div> -->
</model-viewer>
