#Editor CCBs

The Particle System CCB creates a new file with a CCParticleSystem included as the root node.  Since CCParticleSystems cannot take on children, this will be the only node in the file.  For more information about creating particle effects see the section on the Particle System node (link).

##Templates vs CCBs
Since particle systems can be saved in templates, it may seem that there is no need to create a CCB file to contain a particle system rather than dragging it directly from the node library. The advantage of using a particle CCB is that when you update the CCB it will change for every instance - a template only applies the information once and cannot be changed later without creating an entirely new template.