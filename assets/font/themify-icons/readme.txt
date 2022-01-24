

		//function tinh tong cua 1 array
		int tong ( array[], size){
			int sum=0;
			for(int i=0; i<size; i++){
				sum+=array[i];
			}
			return sum;
		}
		
		//function tim A[i],[j]
		int sumswap1, sumswap2; 
		int temp1, temp2;
		
		for (int i = 0; i < n; i++) {
			for (int j = 0; j < m; j++) {
				newsum1 = sum1 - A[i] + B[j];
				newsum2 = sum2 - B[j] + A[i];
				if (newsum1 == newsum2) {
					val1 = A[i];
					val2 = B[j];
				}
			}
		}