
 ____   _        __       ____  ____         ___  ___    ____  ______      ____   __ __      ___ ___  ____   __  _ 
|    \ | |      /  ]     /    ||    \       /  _]|   \  |    ||      |    |    \ |  |  |    |   |   ||    \ |  |/ ]
|  D  )| |     /  /     |  o  ||  o  )     /  [_ |    \  |  | |      |    |  o  )|  |  |    | _   _ ||  D  )|  ' / 
|    / | |___ /  /      |     ||     |    |    _]|  D  | |  | |_|  |_|    |     ||  ~  |    |  \_/  ||    / |    \ 
|    \ |     /   \_     |  _  ||  O  |    |   [_ |     | |  |   |  |      |  O  ||___, |    |   |   ||    \ |     |
|  .  \|     \     |    |  |  ||     |    |     ||     | |  |   |  |      |     ||     |    |   |   ||  .  \|  .  |
|__|\_||_____|\____|    |__|__||_____|    |_____||_____||____|  |__|      |_____||____/     |___|___||__|\_||__|\_|
                                                                                                                   
                                                                                                                   
                                                                                                                   

    Welcome to Magnum's Realistic Loco Control E2!
    Setup Instructions:
    
    Place the E2 onto the back of either the body or a bogie and configure the e2 (see below).
    Wire Active and MU_Master to two separate toggled buttons in the cab, Then wire Pod:entity to your pod "Entity [ENTITY]" NOT "Creat Entity [ENTITY]".
    
    How to hook up MU System:
    Spawn a wire socket at each end of the locomotive (make sure that the "Use array inputs/outputs" box is TICKED)
    Wire the FrontPlugIn and RearPlugIn inputs to each respective sockets (the e2 also has FrontPlugOut and RearPlugOut Outputs that need to be wired)
    Make sure the control locomotive's Master switch (the button that MU_Master is wired to) is on and all the other master switches are off
    Then simply connect the two sockets using two wire plugs!
    
    OR 
    
    Spawn in Anyones MU Linker and use it on the chips! Yes, this does work!
