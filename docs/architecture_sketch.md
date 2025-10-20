# Architecture Sketch
Add an ASCII diagram or image plus brief legend. Include:

    ● View composition / routing (router or view manager)
    ● Top-level module map (≥6 modules): state/, services/, ui/, engine|viz/, routes/, utils/
    ● Core classes (≥3) and responsibilities (model, system/controller, renderer/view)

project/  
├─ index.html # loads  → classes → scenes → game.js (in order)    
├─ assets/ # background.png, player.png, enemy.png, etc.  
└─ src/  
