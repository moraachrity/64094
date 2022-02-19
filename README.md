# 64094

<xml version=¨1.0¨ encoding=¨utf-8?>
  
  <!--DTD-->
  <!DOCTYPE StudentAssm
[
<!ELEMENT Studentname (fname lname)>

_Student
	-Studentid
	+getMySubmissions(StudentId: int)
Submission
	-Subnr: int
	-urL: URL
	+getFeedback(sNr)

Module
	-Code: int
	-term: String


Student {1}-gets all-{1}Submission
Submission{1}-is submitted to-{1}Module

]>
  
  
  
   <!--XML-->
  
<xml version=¨1.0¨ encoding=¨utf-8?>
	
     <student>	         
      <Studentname>
  <fname>¨¨</fname>
	      
   </Studentname>
	     <studentid>
		     </studentid>
		     
	       </student>
	
	
	<submission>
		<date>
  </date>
	<Subnr>
		<Subnr>
			<url>
				</url>
		</submission>
		
		<module>
			<code>
				</code>
			<term>
				</term>
			</module>
  
   <!--JSON-->
  
  
  
<!-- link https://app.gleek.io/diagrams/mG6gZWu1s0kStPSpoJ0fOA -->
  
   <!--HTML links to the class diagrams-->
  
<a href="https://app.gleek.io/diagrams/mG6gZWu1s0kStPSpoJ0fOA" target="_blank">
    <img src="https://sketchertest.blob.core.windows.net/previewimages/mG6gZWu1s0kStPSpoJ0fOA.png" alt="Student marks" title="Student marks" />
</a>
<p>Created with <a href="https://gleek.io">Gleek.io diagram maker </a></p>
  
  <!-- link https://app.gleek.io/diagrams/mG6gZWu1s0kStPSpoJ0fOA -->
  
   <!--HTML links to the reduced class diagram for getAllSubmissions ()-->
  
  <a href="https://app.gleek.io/diagrams/5QSesIG7lDQi6UENwyz7gQ" target="_blank">
    <img src="https://sketchertest.blob.core.windows.net/previewimages/5QSesIG7lDQi6UENwyz7gQ.png" alt="getMySubmissions" title="getMySubmissions" />
</a>
<p>Created with <a href="https://gleek.io">Gleek.io diagram maker </a></p>
