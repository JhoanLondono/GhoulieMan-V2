Work has been done on the animation and functionality of the jump for the playable character. Additionally, 
issues such as the desynchronization between the character's capsule collider and its visual part during 
jumping have been fixed. Limits have been set to prevent infinite jumping by using a layer with a BoxCollider2D 
applied to the platform, along with a boolean that detects collision with an empty object placed under the 
character’s feet.
