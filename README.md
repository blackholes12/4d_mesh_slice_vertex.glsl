# 4d_mesh_slice_vertex.glsl
Currently best way to generate 4d slice by vertex shader,which has generate 10000 4d objects in c++ environment by opengl in lower laptop at 30hz frame/s by me.If each 4d object has 100 tetras be used,it can generate 1,000,000 4d tetras even more by valkan.So,it is a break through in dimension and quantity,it can be used in almost all game engines if you want.
how to use it?
Lets consider the most easy way to generate a 4d tetra,you need at least(4 vec4 points and 1 uint id)struct be defined in cpu code as one tetra and copy and send 
4 tetras to the vertex shader with(id=0,id=1,id=2,id=3)(4 tetras' points are same)


