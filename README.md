# Plus-minus-Hackerank
def positiveNegativeZero(arr):

	
	length = len(arr);

	positiveCount = 0;
	negativeCount = 0;
	zeroCount = 0;

	for i in range(length):
		if (arr[i] > 0):
			positiveCount += 1;
		elif(arr[i] < 0):
			negativeCount += 1;
		else:
			zeroCount += 1;
		
	print("{0:.6f}".format((positiveCount / length)));
  print("{0:.6f}".format((negativeCount / length)));
  print("{0:.6f}".format((zeroCount / length)));
	
	

