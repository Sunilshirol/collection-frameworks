# collection-frameworks
import java.util.HashSet;
import java.util.LinkedHashSet;
import java.util.Set;

public class RemoveduplicateElements {
	public static void main(String[] args) {
		int arr[] = {10,20,10,20,20,30,40,40,30,40,50,60};

		Set<Integer> hSet=new LinkedHashSet<Integer>();
		for (int i = 0; i < arr.length; i++) {
			hSet.add(arr[i]);
		}
		System.out.println(hSet);
	}
}
