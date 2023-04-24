import string

# Function to calculate the similarity percentage
def calculateSimilarityPercentage(matchCount, totalCount):
    return (matchCount / totalCount) * 100.0

# Function to split a string into words
def splitStringIntoWords(s):
    # Remove punctuation and convert to lowercase
    s = s.translate(str.maketrans('', '', string.punctuation)).lower()
    # Split the string into words
    return s.split()

#List of articles with questions
articles_Available = ["alt_article" , "alt_article2" ]
altArticles = [""]
read = input("which article do you want to read?\narticle\narticle2\n\n")
if read == "article":
  i=0
else: 
  i=1

# Open the two files
with open(read) as file1, open(articles_Available[i]) as file2:
    # Read the contents of the files
    file1Content = file1.read()
    file2Content = file2.read()

# Split the contents of the files into words
file1Words = splitStringIntoWords(file1Content)
file2Words = splitStringIntoWords(file2Content)

# Find the differences between the two files
differences = list(set(file1Words) - set(file2Words))

# Calculate the similarity percentage
matchCount = len(file1Words) - len(differences)
totalCount = max(len(file1Words), len(file2Words))
similarityPercentage = calculateSimilarityPercentage(matchCount, totalCount)

# Output the results
print(f"This article is {similarityPercentage:.2f}% percent correct. Different website Suggested. ")
#only print good website if percent is 100
#print("Words that are different between the two files:")
#for word in differences:
    #print(word)