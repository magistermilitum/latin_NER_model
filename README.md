#This is a automatic model to entails automatic entity named recognition on medieval diplomatic charters. 

#Model was trained on a 5 thousands-items database of latin Burgundy documentation. 

#Model have a double core working the one on personal names and the other on place names. Overlapped entities recognition can be entailed setting CRF output. Institutional entity names is not implemented on this model. 

#Tagging of the model can be activated on txt, csv and crf text formats. You must downloads Wapiti CNRS package from: https://wapiti.limsi.fr/#download

###Tagging Order must follow the patter: wapiti label -m ~/model.txt -c ~/input.txt ~/output.txt
