void main() {
  // Define marks
  int marks = 78;

  // Determine grade
  String grade = determineGrade(marks);

  // Print grade
  print('Grade: $grade');
}

// Function to determine grade
String determineGrade(int marks) {
  if (marks > 85) {
    return 'Excellent';
  } else if (marks >= 75 && marks <= 85) {
    return 'Very Good';
  } else if (marks >= 65 && marks < 75) {
    return 'Good';
  } else {
    return 'Average';
  }
}
