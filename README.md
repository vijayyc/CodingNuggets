
# CodingNuggets

## Java

    String testStr;

    byte[] byteArr = testStr.getBytes();

    String[] splitStrArr = testStr.split(" ");

    char [] charArr = testStr.toCharArray();

    List<String> itemsList = Arrays.asList("Static", "items", "as", "list");

	{
		//available for byte, char, double, float, int, short, long, Object
		// All other than T[] methods of binarySearch return the index of the array.
		Arrays.binarySearch(int[] a, int key)		
		Arrays.binarySearch(int[] a, int fromIndex, int toIndex, int key)
		
		//This methods return the object itself from the array
		Arrays.binarySearch(T[] a, int fromIndex, int toIndex, T key, Comparator<? super T> c)
		Arrays.binarySearch(T[] a, T key, Comparator<? super T> c)
	}
	{
		//available for byte, char, double, float, int, short, long, T
		Arrays.copyOf(int[] original, int newLength)
	}
	{
		//available for boolean, byte, char, double, float, int, short, long, T
		Arrays.copyOfRange(float[] original, float from, float to)
	}
	{
		//available for boolean, byte, char, double, float, int, short, long, Object
		Arrays.equals(boolean[] a, boolean[] a2)
	}
    {
		//Available for boolean, byte, char, double, float, int, long, short, Object
		Arrays.toString(byte[] a)
	}

