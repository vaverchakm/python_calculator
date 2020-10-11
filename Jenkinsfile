pipeline { 	
	agent any 	
	stages { 		
		stage("Run the code!") { 			
			steps { 				
				sh """ 					
					python calculator.py 				
				""" 			
			} //steps 		
		} //stage
		stage("Run Unit test"){
			steps {
				sh """
				pytest
				"""
			}//steps
		}//stage 	
	} //stages 
} //pipeline
