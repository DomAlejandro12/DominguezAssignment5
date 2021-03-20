# DominguezAssignment5
# 1. Describe	the	difference	between	the	Gouraud	shading	and	Phong	shading	models.	Include	
# screen	shots	from	your	application	(or	pictures	from	lector	or	online)	to	help	strengthen	# your	discussion. 

The Gouraud model the vertex shader must determine a color for each vertex and pass that color as an out variable to the fragment shader. The color is passed to the fragment shader as an in variable, it is interpolated accros the fragments. Whereas, in the Phong shading model, the vertex shader provides the normal and position data as out variables to the fragment shader. The fragment shader then interpolates these variables and computesthe color.


# Resource: https://www.haroldserrano.com/blog/what-is-the-difference-between-gouraud-and-phong-shading



# 2. The	Phong	reflection	model	includes	several	non-physical	(non-realistic)	components	in	the
# model.	List	and	describe	these	components	that	are	not	realistic	and	describe	why	they	are	
# made.	

In the Phong shading model assuming there is a set of point sources, in this model is assumed that each source have its own separate ambient, diffuse, and specular components for each of the three primary colors, this assumption may appear unnatural but its goal is to make realistic shadding effects as close to real time as possible.



# Resource: https://learn-us-east-1-prod-fleet01-xythos.content.blackboardcdn.com/blackboard.learn.xythos.prod/5a319f5d041da/1335199?X-Blackboard-Expiration=1616036400000&X-Blackboard-Signature=cNHaR%2BqfP8tB6idLsFUhabjSBF4%2FQ%2BF42ee%2Bi%2FV50Kk%3D&X-Blackboard-Client-Id=100903&response-cache-control=private%2C%20max-age%3D21600&response-content-disposition=inline%3B%20filename%2A%3DUTF-8%27%27PhongReflectionModel%25281%2529.pdf&response-content-type=application%2Fpdf&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20210317T210000Z&X-Amz-SignedHeaders=host&X-Amz-Expires=21600&X-Amz-Credential=AKIAYDKQORRYTKBSBE4S%2F20210317%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=3b19d93e7f98a127ec54f6e78ca2d7f8a7922a8596af2690bf6c7eb23ebf003d
